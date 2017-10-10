# 使用方法

```bash
mkdir -p tasks
cd tasks
git clone https://github.com/JenkinsTasks/${tasks}.git

cd -

ant -f sample.xml -p -Dasl.root=. -Dasl.tasks.root=tasks

```
