Description:\
    Controls the Material point Scanner and displays scan results\
    You can turn on the feature to show results in stacks bu changing b=0 to b=1\
    You can turn on the timer feature by changing a=0 to a=1\
    Has optional Tiers version(Tiers versions does not have togglable features)\
    And optional 4 ore display\
Setup:\
    You'll need the Material point Scanner, an button & an 24x24 text panel\
    For the Timer feature you'll need an extra progress bar\
    For the Tier/4 ore version you'll need an extra 24x24 text panel\
        In the Material point Scanner change these values\
            "Active" to "SB"\
            "ScanResults" to "SR"\
            "Material" to "M"\
            "Volume" to "V"\
            "Reset" to "RR"\
        Change in the button the variable "ButtonState" to "SB"\
        Change in the text panel the variable "PanelValue" to "SD1"\
    For when using the Timer feature also do:\
        Change in the progress bar the variable "PanelValue" to "SDelay"
    For when using the Tier/4 ore version also do:\
        Change in the text panel the variable "PanelValue" to "SD2"
