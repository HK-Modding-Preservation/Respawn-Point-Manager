# Respawn Point Manager

Custom respawn points for Hollow Knight: create, cycle, teleport, save presets.

Свои точки респавна в Hollow Knight: создание, перебор, телепорт, пресеты.

## Settings / Настройки

| Option | Values | EN | RU |
|---|---|---|---|
| Show Counter | On / Off | Point counter on the HUD | Счётчик точек на HUD |
| HUD Position | Screen Edge / Beside Geo / Far From Geo | Where to put it | Куда его поставить |
| Teleport Mode | Single Scene / Multi Scene | Single wipes points on room change, Multi keeps them | Single стирает точки при смене комнаты, Multi сохраняет |
| Checkpoint Mode | Auto / Manual | Auto turns the game's own checkpoints into points, Manual ignores them | Auto делает чекпоинты игры точками, Manual их игнорирует |
| Ignore Entry Checkpoint | On / Off | Room entry checkpoint doesn't count as a point | Чекпоинт на входе в комнату не считается точкой |
| Hold On Air Checkpoint | On / Off | Keeps the Knight on a mid-air point until control returns | Держит рыцаря на точке в воздухе, пока не вернётся управление |
| Cross-Scene Respawn | On / Off | No points in this room: respawn at the previous point in its own scene | Если в комнате нет точек — респавн на предыдущей точке в её сцене |
| Checkpoint Texture | Geometry Dash / Celeste / Deltarune / IWBTG / Custom | Point icon; Custom reads `image.png` from the mod folder | Иконка точки; Custom берёт `image.png` из папки мода |
| In-Scene Checkpoints | All / Current Only / None | Which points get drawn in the scene | Какие точки рисовать в самой сцене |

## Keybinds / Клавиши

| Key | EN | RU |
|---|---|---|
| 1 | Previous point / teleport to current | Предыдущая точка / телепорт на текущую |
| 2 | Next point | Следующая точка |
| 3 | Tap: create point, hold: delete last | Тап — создать точку, зажать — удалить последнюю |
| 4 | Hold: clear all | Зажать — очистить все |
| 5 | Save preset | Сохранить пресет |
| 6 | Preset menu | Меню пресетов |

Presets are stored in / Пресеты лежат в:
`%USERPROFILE%/AppData/LocalLow/Team Cherry/Hollow Knight/RespawnPointManager/Presets`
