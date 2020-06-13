# graphviz-ubuntu-img
Graphviz docker image

Clone repo and cd to clonned dir
```bash
git clone ... path/to/clonned-dir
cd path/to/clonned-dir
```

Create image
```bash
docker build $(pwd) -t graphviz-ubuntu-img 
```

Generate example graph with following command:
```bash
docker run -v $(pwd):/ws graphviz-ubuntu-img dot -v -Tpng -oex.png ex.gv
```
You should see a result in a png file named as `ex.png`.
