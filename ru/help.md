---
title: Помощь
layout: default-ru
---



<!-- GENERATED FILE -- DO NOT EDIT -->



# Часто задаваемые вопросы

- [Общее](#general)
- [Группы](#groups)
- [Шифрование](#encryption)
- [Мульти-клиент](#multiclient)
- [Прочее](#miscellaneous)

# Общее

## Кому я могу написать?

- С помощью Delta Chat вы можете написать на любой существующий адрес электронной почты, даже если получатель не использует (пока) приложение Delta Chat. Это одно из самых больших отличий от других мессенджеров: у получателя нет необходимости устанавливать то же приложение, что и у вас.

## Каковы преимущества Delta Chat по сравнению с другими мессенджерами?

- _Независимый_ от любой компании или службы. _Вы_ владеете собственными данными. 
- Ваши данные не сохраняются на центральном сервере; таким образом, в отличие от большинства других мессенджеров, Delta Chat защищает даже ваши метаданные (кто пишет и кому)
- Вы никому не распространяете свою адресную книгу.
- _Быстрота_ благодаря использованию протокола Push-IMAP
- _Огромное количество пользователей_ - получателей, _не_ использующих Delta Chat, также могут получать от вас сообщения
- _Совместимо_ - не только с собой
- _Лёгкий_ и _элегантный_ пользовательский интерфейс
- _Распределённая_ система
- _Нет спама_ - по умолчанию отображаются только сообщения от известных пользователей
- _Надежный_ - безопасно для профессионального использования
- _Заслуживающий доверия_ - можно использовать даже для деловвой переписки
- Полностью _открытый исходный код_ и основан на _стандартах_

## What if the receiver does not use Delta Chat?

- Получатель получит обычное письмо - если он ответит на него, вы увидите ответ в приложении Delta Chat.

Какие сообщения отображаются в Delta Chat?

Delta Chat автоматически показывает ...

- Сообщения от контактов в вашей **адресной книги**
- Сообщения от контактов, которым **вы писали сами**
- **Ответы** на сообщения отправленные вами

Другие сообщения не отображаются автоматически. Вы можете посмотреть другие сообщения в пункте главного меню **Почтовый ящик** и, при желании, начать чат оттуда.

## Как насчёт спама?

- Так как сообщения от совершенно неизвестных контактов не появляются автоматически, как правило, **спама нет**.
- Однако, если действительно нужно, вы можете **заблокировать** любой контакт.

## Does Delta Chat support images, videos and other attachments?

- Да. Помимо обычного текста, все вложения электронной почты отображаются в виде отдельных сообщений. Исходящие сообщения автоматически получают вложения.

## Поддерживает ли Delta Chat HTML-письма?

- Да. Если во входящей электронной почте отсутствует блок обычного текста, мы преобразуем HTML-письма в обычный текст самостоятельно. Исходящие письма всегда используют обычный текст.

# Группы

## Как создать группу?

- Выберите **Добавить группу** в выпадающем меню в левом верхнем углу начального экрана приложения.
- На следующем экране выберите **участников группы** и установите флажок в правом верхнем углу. После этого можно определить **имя группы**.
- Как только вы пишете **первое сообщение** в группе, все участники информируются о новой группе и могут ответить в группе (до тех пор, пока вы не пишете сообщение в группе, группа невидима для участников).

## Кто может добавлять участников в группу?

- Каждый участник группы имеет **те же права**, что и любой другой. По этой причине каждый может удалить любого участника или добавить нового.
- Чтобы добавить или удалить участников, нажмите на название группы в чате.

## Я случайно удалился.

- Поскольку вы больше не являетесь участником группы, вы не можете добавить себя снова. Тем не менее, никаких проблем, просто попросите любого другого участника группы в обычном чате добавить вас снова.

## Я больше не хочу получать сообщения группы.

- Удалите себя из списка участников или удалите весь чат. Если вы захотите присоединиться к группе позже, попросите другого участника группы добавить вас снова.
- В качестве альтернативы, вы также можете "заглушить" группу - сделав это, вы будете получать все сообщения и по-прежнему сможете писать, но вы больше не будете уведомлены о каких-либо новых сообщениях.

# Шифрование {#encryption}

## Delta Chat поддерживает сквозное шифрование?

- Да.

## Что нужно сделать, чтобы активировать сквозное шифрование?

- Ничего.

- Delta Chat (and other [Autocrypt](https://autocrypt.org)-compatible email-programs) share the keys required for end-to-end-encryption automatically as the first messages are sent. After this, all subsequent messages are encrypted end-to-end automatically. If, one of the chat partners use an app later that cannot use end-to-end-encryption, it is paused for this time and automatically re-activated as soon as possible.

- Если вы хотите _отключить_ сквозное шифрование, используйте соответствующий пункт в меню "Настройки / Расширенные настройки".

## Если сквозное шифрование недоступно, связь не шифруется вообще?

Не так. Тогда используется обычное _транспортное шифрование_, стандартное для электронной почты.


## Как проверить шифрование?

- If a little **padlock** is shown beside a message, this implies that the message is end-to-end-encrypted _and_ is send from the given sender _and_ your answer will be end-to-end-encrypted as well.
- If there is **no padlock**, the message is usually transport encrypted eg. because you or the sender have disabled end-to-end-encryption or the sender uses an app that does not support end-to-end-encryption.


## How can I verify the sender?

The user's profile shows some additional information:

- For an end-to-end-encryption, Delta Chat show two fingerprints there. If they are the same on the device of your chat partner, the connection is safe.
- For transport encryption, this state is just shown there


## Which standards are used for end-to-end-encryption?

- Стандарт OpenPGP. Обмен ключами осуществляется через [Autocrypt](https://autocrypt.org).

## Можно ли использовать существующий закрытый ключ?

- Да. The best way is to send an Autocrypt Setup Message from the other e-mail client. Look for sth. like **Start Autocrypt Setup Transfer** in the settings of the other client and follow the instructions shown there.

- Alternatively, you can import the key manually at "Advanced settings / Manage private keys". Caution: Make sure, the key is not protected by a password or remove it before.

Если у вас нет ключа или вы даже не знаете, что он вам понадобится - не волнуйтесь: Delta Chat сгенерирует его при необходимости, вы не должны ничего делать.

# Мульти-клиент {#multiclient}

## Могу ли я использовать Delta Chat на нескольких устройствах одновременно?

- Если вы хотите использовать **одну и ту же учётную запись** на разных устройствах, вы должны убедиться, что все устройства используют одни и те же ключи шифрования:

 - На первом устройстве выберите "Дополнительные настройки / Управление закрытыми ключами / Экспорт ключа"
 - Через USB скопируйте файл ключа из каталога "Загрузки" первого устройства на второе.
 - На втором устройстве выберите "Дополнительные настройки / Управление закрытыми ключами / Импорт ключа"

- Всё это **не требуется** для стандартного использования Delta Chat с помощью только одного устройства.

- Примечание: в многопользовательской режиме, _входящие_ сообщения отображаются сразу на всех клиентах. _Исходящие_ сообщения синхронизируются два раза в час. Возможно мы можем это улучшить, но нам требуется дополнительная поддержка по данному вопросу.


# Прочее

## Delta Chat на компьютере с GNU/Linux

- Вы можете запустить Delta Chat на компьютере с Ubuntu Linux (или другом дистрибутиве GNU/Linux, поддерживающем формат пакетов snap) путём простой установки [Anbox](https://anbox.io) через терминал:

  $ *sudo snap install \-\-classic anbox-installer && anbox-installer*

- Чтобы добавить приложение Delta Chat, загрузите файл *com.b44t.messenger_433.apk* с домашней страницы и установите через терминал:

  $ *adb install path/to/com.b44t.messenger_\<version\>.apk*

adb - это утилита Android Debug Bridge и она может быть установлена из репозитория

- Instead of installing Delta Chat directly via APK file, you can first install the F-Droid store via [F-Droid-APK](https://f-droid.org/FDroid.apk) and then install Delta Chat using the store. The great benefit is the information about updates and the migration of existing config and chat data.


## Проблемы со входом

У меня проблема с ...

- Gmail: Включите "Поддержка менее безопасных приложений" и IMAP (вы можете получить письмо, чтобы предоставить разрешение)

## Меня интересуют технические детали. Можете рассказать больше?

- Смотрите на странице [Стандарты используемые Delta Chat]({% include standards-url %}).
