# leetcode_summary
趁著這次要開始準備面試，整理了一下這些時間內寫過的leetcode與一些解題中的想法。雖然想要Java與Python都刷，不過還是先以Python的解法為主。  
由於解題的紀錄越來越多, 為了好維護將解題紀錄依難度拆成了三個檔案, 這邊只留下連結  

演算法:  
  * -[x] <a href="Easy/README.md">Easy </a>
  * -[x] <a href="Medium/README.md">Medium </a>
  * -[x] <a href="Hard/README.md">Hard </a>

## 如何用docker開啟jupyter-lab
為了簡化(~複雜化~)開啟jupyter-lab的方法,特地去查了一下還真的有image

這邊使用的指令是:

```
podman run --rm -p 8889:8888 -v "$(pwd)":/home/jovyan/work quay.io/jupyter/base-notebook start-notebook.py --NotebookApp.token='my-token'
```

$(pwd):想要使用的本機端資料夾  