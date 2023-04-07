# debInjector

DebInjector is a simple bash script that allows you to inject a bash payload into a Debian package.

## Usage
 
 

    sudo debinjector -d <deb_package> -b <bash_script>
 
 
 ### Options
 
    -h, --help          Display this help menu
    -v, --version       Show program's version number and exit
    -d  Debian package  Target Debian package
    -b  bash script     Bash script containing payload


 ### Example
 
      sudo debinjector -d package.deb -b payload.sh
      
      
[Click to view the video](https://drive.google.com/file/d/VIDEO_FILE_ID/view?usp=sharing)


 ## Contributions

Contributions are always welcome! If you have an idea for a new feature or have found a bug, please open an issue.
