# This is a PDF

## TiddlyWiki transclude sample


template of pdf
```
!pdf
<html>
  <div align="center">
    <embed width="$1px" height="$2px" src="$3" type="application/pdf" ></embed>
  </div>
</html>
!end
```

to use for transclude tiddler
```
<<tiddler [[embed##pdf]] with:"500" "300" "./pdf/sample_pdf.pdf">>
```
