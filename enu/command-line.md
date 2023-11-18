# Command Line Reference
```
Usage: imgdrive [Switches] [ImageFile]

Switches:
  -m:DriveLetter ImageFile     Mount image file to the specified DriveLetter drive
  -m:DriveID ImageFile         Mount image file to the specified DriveID drive
  -m:DriveTag ImageFile        Mount image file to the specified DriveTag drive
  -m ImageFile                 Mount image file to drive 1
  -u:DriveLetter               Unmount the specified DriveLetter drive
  -u:DriveID                   Unmount the specified DriveID drive
  -u:DriveTag                  Unmount the specified DriveTag drive
  -u ImageFile                 Unmount image file
  -u                           Unmount all drives
  -l                           List all drives

Examples:
  -m:1 c:\foo.iso              Mount c:\foo.iso to drive 1
  -m:d c:\foo.iso              Mount c:\foo.iso to drive D:
  -m:movies c:\foo.iso         Mount c:\foo.iso to drive tagged movies
  -m:1 c:\foo\                 Mount folder c:\foo\ to drive 1
  -m:d c:\foo\                 Mount folder c:\foo\ to drive D:
  -m:movies c:\foo\            Mount folder c:\foo\ to drive tagged movies
  -u:1                         Unmount drive 1
  -u:d                         Unmount drive D:
  -u:movies                    Unmount drive tagged movies
  -u                           Unmount all drives

Notes:
  All parameters are case-insensitive
  Switches can start with a slash / or dash -
  DriveLetter with a letter from D to Z
  DriveID with a number from 1 to 4 (Up to 9 in Pro version)
  Use drive 1 if no DriveLetter/DriveID/DriveTag is specified
```

## Installer Reference
```
imgdrive_x.x.x.exe -s          Silent install mode
```