# graphviz-ubuntu-img
Graphviz docker image

Generate example graph with following command:
```bash
docker run -v $(pwd):/ws graphviz-ubuntu-img dot -v -Tpng -oex.png ex.gv
```
You should see a result in a png file named as `ex.png`.
