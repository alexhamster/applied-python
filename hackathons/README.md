Заливать игры в папку games
===============

Вам нужно отнаследовать класс вашей игры от класса BaseGame, лежащего в py-файлике BaseGame, а класс хранилища от Storage
В BaseGame нужно реализовать метод run, запускающий вашу игру
Чтобы в течении игры писать ваши очки в хранилище, нужно вызывать у игры метод add_scores(self, point), где point - число очков
Так же в файле(не в классе) должна быть константа NAME с именем вашей игры

