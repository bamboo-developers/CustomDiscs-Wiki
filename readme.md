# Custom Discs for Paper 1.16.5
### Разработан специально для [Bambooland](https://discord.com/invite/bambooland-919189180360318976)

- Воспроизведение пользовательских музыкальных дисков с использованием API простого голосового чата. (Мод голосового чата требуется на клиенте и сервере.)
- Используйте ```/customdisc``` или ```/cd```, чтобы создать пользовательский диск.
- Музыкальные файлы должны быть в форматах ```.wav```, ```.flac``` или ```.mp3```.

Загрузка файлов:
- Для загрузки файла используйте команду ```/cd download <url> <имя_файла.расширение>```. Ссылка, используемая для загрузки файла, должна быть прямой (то есть файл должен начать загружаться автоматически при доступе по ссылке). Файлы должны иметь правильное указанное расширение. В консоли сервера будет вызвано исключение UnsupportedAudioFileException, если расширение файла неправильное (например, при попытке дать файлу формата wav расширение mp3). Ниже приведен пример использования команды и ссылка для получения прямых загрузок из Google Drive.
- Пример: ```/cd download https://example.com/mysong "mysong.mp3"```
- Ссыслка на гугл диск https://drive.google.com/drive/
  - Прямые ссылки Google Drive: https://lonedev6.github.io/gddl/

Зависимости:
- Для того чтоб у вас работали кастомные пластинки вам необходим мод [simple voice chat](https://modrinth.com/plugin/simple-voice-chat/versions?c=release)

## [Пример установки музыки на пластинку](https://www.youtube.com/watch?v=-AO_43wQgD0)


_By bamboo-developers_
