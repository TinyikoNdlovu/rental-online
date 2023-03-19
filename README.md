# Django Rental Final Project for Power Learn Project Programme 

### A functional project written in Django

## How to tweak this project for your own uses

``
Since this is a skills based project I'd encourage you to clone and rename this project to use for your purposes.
``

```
from django.contrib import admin
from django.urls import path, include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('apartmentroom/', include('apartmentroomapp.urls')),
]
```

## Find a bug?
 ``
 If you found an issue or would like to submit an improvement to this project, please submit an issue using tab above. If you would to submit a PR with a fix, reference the issue you create!
 ``

 ## Known issues (Work in progress)
 ``
 This project is still ongoing. The user Authetication of the apartmentroomapp has t been started yet. This is coming soon!
 ``