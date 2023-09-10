# MdFactory

MdFactory és un conjunt d'eines per a la creació de documentació fent ús del llenguatge Markdown.

El motor amb què generem els documents és Pandoc, tant per a PDF com per a web, el que ens permet  fer del mateix font sense haver de realitzar cap canvi per generar l'eixida. 

Les eines de mdfactory fan ús d'altres eines, com la plantilla Eisvogel per generar PDFs.

A la carpeta `exemple` podeu trobar un exemple més o menys complet que es pot fer servir de plantilla.

Aquesta carpeta d'exemple está composta de tres documents, amb informació sobre MDFactory, pel que podeu documentar-se també amb ells:

* [Alguns aspectes de Markdown relacionata amb MDFactory](exemple/1.Markdown.md)
* [El fitxer content.yaml](exemple/2.contentYAML.md)
* [Ordres de MDFactory](exemple/3.ordres.md)

# Requeriments

Per al correcte funcionament de les eines, es requereix d'una versió de Pandoc superior a la 2.19.2-1. Podeu trobar les últimes versions pera Ubuntu a [https://github.com/jgm/pandoc/releases](https://github.com/jgm/pandoc/releases)

A banda de la instal·lació del paquet deb, són necessaris alguns paquets i versions concretes de python.

En primer lloc, instal·larem pip amb:

```
sudo apt install python3-pip
```

I després instal·lem els paquets `panflute` (versió 1.12.5):

```
$ sudo pip install panflute==1.12.5
```

I pandoc-latex-environment:

```
sudo pip install pandoc-latex-environment
```

