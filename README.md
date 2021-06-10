```  
latex skeleton.ins
[pdf]latex skeleton.dtx
makeindex -s gind.ist -o skeleton.ind skeleton.idx
makeindex -s gglo.ist -o skeleton.gls skeleton.glo
[pdf]latex skeleton.dtx
[pdf]latex skeleton.dtx
```
