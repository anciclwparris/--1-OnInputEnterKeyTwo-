# --1-OnInputEnterKeyTwo-
GUICtrlSetOnEvent(-1, "OnInputEnterKeyTwo")     If $GuiChild Then         GUICtrlCreateButton("flash child", 220, 8, 120, 25)         GUICtrlSetOnEvent(-1, "OnFlashBttn")         GUISetState(@SW_SHOW, $GuiChild)         OnFlashBttn()     EndIf     MainLoopExample() EndFunc Func MainLoopExample()     While 1         Sleep(100)     WEnd EndFunc Func OnInputEnterKeyOne()
