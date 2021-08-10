# Enter-Plus-Plus
Tired of forgetting semicolons? I created this macro to help. (Mostly as a joke.)
This macro is used by hitting Ctrl+Enter, it's the same as typing a semicolon then hitting the enter key.
You may need to edit your Notepad++ shortcuts, if anything is already assigned to Ctrl+Enter this won't work.


<NotepadPlus>
    <InternalCommands>
    </InternalCommands>
    <Macros>
        <Macro name="Enter++" Ctrl="yes" Alt="no" Shift="no" Key="13">
            <Action type="1" message="2170" wParam="0" lParam="0" sParam=";" />
            <Action type="1" message="2170" wParam="0" lParam="0" sParam="&#x000D;" />
            <Action type="1" message="2170" wParam="0" lParam="0" sParam="&#x000A;" />
        </Macro>
    </Macros>
    <UserDefinedCommands />
    <PluginCommands />
    <ScintillaKeys />
</NotepadPlus>
