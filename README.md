# scaffold-configs
YAML templates for [Scaffolder](https://github.com/cemister/scaffolder)

## Usage
all your scaffolder YAML configs should be stored in scaffolder-configs folder in your home directory. (~/scaffolder-configs for Unix, %USERPROFILE%/scaffolder-configs for Windows). Make sure to create it and populate it with configs you need.
 
(Replace cpp.yaml with needed config and hello to your actual project name)

### Linux
```bash
cd ~/scaffolder-configs && wget -q https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml
```
### macOS
```bash
cd ~/scaffolder-configs && curl -s -O https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml
```
### Windows
```bash
cd %USERPROFILE%/scaffolder-configs
curl -s -o cpp.yaml https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml
```
### Run
```bash
scaffold --name hello --yaml "cpp.yaml"
```

Those are templates; feel free to fork this repo and modify them or make your own.
After making a commit, the raw content will update only after ~5 minutes. So make sure that 5 or more minutes passed since you ran the tool and got error AND since last commit here before creating an issue. 

