# PowerShell-1-D-couverte-du-langage

## cp

### Commande pour le PowerShell:
```sh
Copy-Item "C:\User\Logfiles\exemple.txt" -Destination "C:\User\Bureau\exemple"
```

- La commande "Copy-Item" permet de copier un fichier a partir d'un document
- le "-Destination" permet de placer le fichier a l'endroit qui nous intéresse

## rm

### Commande pour le PowerShell:
```sh
Remove-Item C:\Test\*.*
```

- La commande "Remove-Item" permet de supprimer un fichier ou un dossier

## cd

### Commande pour le PowerShell:
```sh
Set-Location -Path "HKLM:\"
```

- La commande "Set-Location" permet de se déplacé dans différent dossier
- Le "-Path" permet d'indiqué l'emplacement d'un dossier ou on veut aller

## mkdir

### Commande pour le PowerShell:
```sh
New-Item -Path "c:\" -Name "logfiles" -ItemType "directory"
```

- La commande "New-ITem" permet de crée un fichier ou un dossier
- Le "Path" permet d'indiquer l'emplacement ou on veut crée le fichier/Dossier
- Le "-Name" permet de donner le nom du fichier/Dossier
- Le "-ItemType" permet d'attribuer si c'est un fichier (file) ou un dossier (directory)

## man

### Commande pour le PowerShell:
```sh
Get-Help ****
```

- La commande "Get-Help" permet de définir une commande a la place du "****"

## history

### Commande pour le PowerShell:
```sh
Get-History
```

- La commande "Get-History" permet d'obtenir la liste des commandes utilisé

## alias

### Commande pour le PowerShell:
```sh
Set-Item -Path alias:np -Value "c:\windows\notepad.exe"
```

- La commande "Set-Item" permet de crée un alias
- La "-Path" permet de crée le nom d'un executable
- La "-Value" est l'executable de base avant la modification de l'alias

## cat

### Commande pour le PowerShell:
```sh
Get-Content -Path .\text.txt 
```

- La commande "Get-Content" permet de vérifier le contenu du fichier
- Le "-Path" permet de séléctionner le fichier qui nous intéresse
