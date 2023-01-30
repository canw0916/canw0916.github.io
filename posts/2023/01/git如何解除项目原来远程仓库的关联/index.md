# Git如何解除项目原来远程仓库的关联


有时候我们需要将一个项目上传到另一个远程仓库，那么就需要解除原来的仓库关联。

1.首先切换到项目的根目录，查看项目原有的remote。

```bash
git remote -v
```

2.接下来就是接触与原来远程仓库的关联。

```bash
git remote rm “remote名称”
```

3.取消git初始化。

```bash
rm -rf .git
```


---

> 作者: [火山](https://canw0916.github.io/)  
> URL: https://canw0916.github.io/posts/2023/01/git%E5%A6%82%E4%BD%95%E8%A7%A3%E9%99%A4%E9%A1%B9%E7%9B%AE%E5%8E%9F%E6%9D%A5%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%93%E7%9A%84%E5%85%B3%E8%81%94/  

