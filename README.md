# scaffold-configs
YAML templates for [Scaffolder](https://github.com/cemister/scaffolder)

## Usage
You can do it like this 
(Replace cpp.yaml with needed config and hello to your actual project name)

### Linux
```bash
wget https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml && scaffold --name hello --yaml "./cpp.yaml" && rm cpp.yaml
```
### macOS
```bash
curl -O https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml && scaffold --name hello --yaml "./cpp.yaml" && rm cpp.yaml
```
### Windows
```bash
curl -o cpp.yaml https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml && scaffold --name hello --yaml "./cpp.yaml" && del cpp.yaml
```

Those are templates; feel free to fork this repo and modify them or make your own.
After making a commit, the raw content will update only after ~5 minutes. So make sure that 5 or more minutes passed since you ran the tool and got error AND since last commit here before creating an issue. 

