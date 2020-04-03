# Add-Featured-Media-To-Wp-API-Posts

Add [this code](https://github.com/JaisonPeres/Add-Featured-Media-To-Wp-API-Posts/blob/master/add-this-to-functions-end.php) to the end of your theme functions.php

This file is usually located at the root of your theme folder, such as:

```
/wp-content/themes/yourtheme/functions.php
```

after that, the posts endpoint will return something like

```json
{
  "thumb_url": "https://yousite.com/wp-content/uploads/2020/03/somefile.jpg",
}
