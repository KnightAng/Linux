Input:
    
    sudo touch /usr/share/applications/Matlab.desktop
    sudo gedit /usr/share/applications/Matlab.desktop

Input:

    #!/usr/bin/env xdg-open
    [Desktop Entry]
    Version=R2019b
    Type=Application
    Terminal=false
    Name=MATLAB
    Exec=/usr/bin/env xdg-openlocal/MATLAB/R2019b/bin/matlab -desktop
    Icon=/usr/local/MATLAB/R2019b/bin/glnxa64/cef_resources/matlab_icon.png
    Comment=Accelerating the pace of engineering and science
