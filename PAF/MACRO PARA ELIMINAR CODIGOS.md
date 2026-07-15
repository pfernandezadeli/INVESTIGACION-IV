Sub QuitarCodigosUnicosDeCitas()
    Dim rngStory As Range
    Dim rngNext As Range

    For Each rngStory In ActiveDocument.StoryRanges
        Set rngNext = rngStory

        Do
            With rngNext.Find
                .ClearFormatting
                .Replacement.ClearFormatting
                .Text = "\[[A-Za-z0-9]{4}\]\[([0-9]@)\]"
                .Replacement.Text = "[\1]"
                .Forward = True
                .Wrap = wdFindStop
                .Format = False
                .MatchWildcards = True
                .Execute Replace:=wdReplaceAll
            End With

            Set rngNext = rngNext.NextStoryRange
        Loop Until rngNext Is Nothing
    Next rngStory

    MsgBox "Listo: se eliminaron los códigos únicos y se conservó la numeración.", vbInformation
End Sub