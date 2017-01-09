#File picker for windows platform
This plugin enables use to select files using native file selector dialog in windows. 


### Simple Usage ###

```javascript
   window.plugins.WindowsFilePicker.open([], function (uri) {
      
      alert(uri);
      
    }, function (error) {
      
        alert(error);
    
    });
```

### Filtering by extension ###
You can also provide specific file type such as ```*.pdf, *.docx.```
By default it will display all file types ```(*.*)```

```javascript
   window.plugins.WindowsFilePicker.open(["*.pdf","*.docx"], function (uri) {
      
      alert(uri);
      
    }, function (error) {
      
        alert(error);
    
    });
```
