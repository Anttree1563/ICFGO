# ICFGO

*   Inter-procedural Control Flow Graph Obfuscation Tool for Android



## Usage

*   For Activity (or AppCompatActivity)

```java
ICFGO icfgo = new ICFGO(Activity, complexity, parentLayoutId)
icfgo.execute();
```

*   General

```
 - ICFGO
 @param Activity 				Activity(Compat) or BaseActivity that will initialize obfuscation
 @param complexity				Number of dummy views that will be used as entry point
 @param parentLayoutId			ID of layout Resource file, such as R.layout.activity_main
```



