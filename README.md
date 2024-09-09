# abc02 - Logic Apps Standard with local function code lab
Lab to create an internal Logic Apps Standard to be deleted at some point.

This is just created to lab with issues with creating a Logic App Standard with a functions code and have it to work after cloning.

Related to issue [5458](https://github.com/Azure/LogicAppsUX/issues/5458) 
In my case the problem was that Logic Apps is dependent on local.settings.json which is included in ignore files. Also I found that I needed to add some ignore files to skip `bin`, `obj` and `lib` folders.

