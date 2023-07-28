# Pour tester sur notre projet de fin d'etude

### Clone   repo

```shell
git clone https://github.com/Issa-barry/my-archi22.git
cd my-archi22
```

* `ng serve` -  Run serveur".
* `ng g c dossier/nom_component` - Créer un component.
* `ng g c dossier/nom_component -m=nom_module` - Créer un component en precisant le module rattacher `.
* `ng lint` - runs `tslint` on the project files.
 




#### demarer le serveur
`
ng serve

`
#### Créer un component
```
ng g c dossier/nom_component
``` 

#### Créer un component en precisant le module rattacher
```
ng g c dossier/nom_component -m=nom_module
```
#### Créer un module
```
ng g m dossier/nom_module --routing=true --module app.module  

```

#### Créer un module avec exemple 2
 
```
ng g m dossier/nom_module  --route nom_autre_routing_moudule --module app.module 

```

#### Créer un Service
 
```
ng g s dossier/nom_service 

```

#### Créer une Directive
 
```
ng g d dossier/nom_directive

```
#### Créer un Guard
 
```
ng g g dossier/nom_guard

```
#### Créer une interface
 
```
ng g i dossier/nom_interface 

```
#### Créer un Classe
 
```
ng g cl dossier/nom_classe 

```

#### Créer un Pipe
 
```
ng g p dossier/nom_pipe 

```