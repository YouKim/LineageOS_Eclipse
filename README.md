# LineageOS_Eclipse
Setup Eclipse IDE for lineageOS java development.

When Android java development, I prefer extract java resource from source tree because:
  - fast file search.
  - fast indexing.

How to use:
  - Build source, However, full build is not required.
  - Building [framework/base] and [framework/base/service] is enough for jave development.
  - Place cplineage.sh into anywhere you want and chmod +x.
  - Edit top 2 lines in cplineage.sh

```sh
LINK_SOURCE=~/lineage                  <--- SOURCE LOCATION
LINK_TARGET=~/eclipse/java/lineage     <--- TARGET LOCATION
```  
  
  - Run cplineage.sh
  - Place .classpath file into TARGET LOCATION
  - Open java project in Eclipse using TARGET LOCATION.
  - Enjoy!
