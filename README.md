# arcaneFEM_API_Doc



```bash
git submodule add https://github.com/jothepro/doxygen-awesome-css.git
cd doxygen-awesome-css
git checkout v2.4.1
```

```bash
git submodule add  https://github.com/arcaneframework/arcanefem.git
```



### To update submodules ### 


```
git submodule update --remote
```



### to create ###

```bash
cd arcanefem/docs && \
	doxygen -w html ./../../apidoc/header.html ./../../apidoc/delete_me.html ./../../apidoc/delete_me.css && \
	doxygen webdoc.doxyfile.in && \
	cd -
```

