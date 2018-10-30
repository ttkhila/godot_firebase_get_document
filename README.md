# GodotFireBase
GodotFireBase é um módulo que permite a integração dos serviços do FireBase nos projetos desenvolvidos com a Godot.

Adaptado de `https://github.com/FrogSquare/GodotFireBase` e de `https://github.com/Dhciolfi/GodotFireBase`

Este último serve como base para quase todas as interações com o módulo, exceto o especificado abaixo em "ADIÇÕES AO MÓDULO"

## Depende De

> Godot game engine (3.0): `git clone https://github.com/godotengine/godot`

> GodotSQL: `git clone https://github.com/FrogSquare/GodotSQL`


## ADIÇÕES AO MÓDULO

## Firebase Firestore

### Ler
Carregar dados de um documento específico:
```
firebase.get_document("collection_name", "document_name")
```
Retorna os documentos em JSON para:
```
from = "Firestore", key = "QueryDocument"
```

## Eventos de Log
Utilize o comando abaixo para observar os logs emitidos pelo dispositivo:
```
adb -d logcat godot:V FireBase:V DEBUG:V AndroidRuntime:V ValidateServiceOp:V *:S
```
