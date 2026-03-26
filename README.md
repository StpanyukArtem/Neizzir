# NEIZZIR Source Code

Декомпилированный исходный код приложения NEIZZIR для Black Russia Online.

## Структура

```
smali/
└── com/blackhub/bronline/neizzir/
    ├── activities/
    │   ├── hudeditor/
    │   └── main/
    │       ├── commands/
    │       ├── explorer/
    │       ├── game/
    │       ├── sens/
    │       ├── settings/
    │       ├── status/
    │       ├── ui/
    │       ├── updates/
    │       └── util/
    ├── converter/
    ├── deeps/
    ├── fragments/
    │   ├── custom/
    │   ├── help/
    │   ├── hitbox/
    │   ├── hpbar/
    │   ├── sborks/
    │   └── weapon/
    ├── service/
    │   ├── time/
    │   └── websocket/
    ├── typefaces/
    ├── video/
    ├── Main.smali
    ├── Utils.smali
    └── KolsonLibrary.smali
```

## Ключевые компоненты

### Core
- `Main.smali`
- `Utils.smali`
- `KolsonLibrary.smali`

### Security
- `activities/main/util/KeyManager.smali`
- `activities/main/util/DeviceInfoSender.smali`
- `activities/main/util/ServerAntiCheatZipManager.smali`

### Network
- `service/websocket/WebSocketService.smali`

### Editors
- `activities/hudeditor/HudEditorActivity.smali`
- `fragments/hitbox/HitboxEditorFragment.smali`
- `fragments/hpbar/HpBarEditorFragment.smali`
- `fragments/weapon/`

### Sborki
- `fragments/sborks/NeizzirSborksFragment.smali`

### Converters
- `converter/BtxPngConverter.smali`
- `converter/NativeDecoder.smali`

## Технологии

- Kotlin → Smali
- Android SDK
- OkHttp3
- WebSocket
- Kotlin Coroutines
- Dagger 2

## Декомпиляция

Использован apktool для извлечения smali кода из APK файла.
