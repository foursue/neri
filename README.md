neri
====

neri(ねり)はslackbotです。

## Description

neriはrubotyを使って各プラグインを付け加えています。

## Install

事前にBOT用のアカウントをSlackで作っておきます。

```
git clone git@github.com:foursue/neri.git
cd neri
vi .env
--------
SLACK_TEAM=***TEAM_NAME***
SLACK_ROOM=***ROOM_NAME***
SLACK_USERNAME=***BOT_USERNAME***
SLACK_PASSWORD=***BOT_PASSWORD***
--------
```

## Usage

```
bundle exec ruboty --dotenv &
```

## Contribution

```
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request
```

## Licence

[MIT](https://github.com/foursue/neri/blob/master/LICENCE)

## Author

[foursue](https://github.com/foursue)
