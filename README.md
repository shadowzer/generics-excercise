# Реализовать коллекцию SavedList

Задание
- Реализовать класс SavedList, представляющий собой список элементов с произвольным доступом, копия которого хранится в виде файла на жестком диске.
- SavedList должен обновлять содержимое файла при каждом изменении списка элементов.
- При создании нового экземпляра SavedList с указанием существующего файла, он должен загрузить список элементов из этого файла.
- SavedList должен корректно обрабатывать ситуацию отсутствия файла (отсутствие файла означает отсутствие элементов в списке).
- Для хранения списка в оперативной памяти можно использовать коллекции из java.util.
- Для сохранения и загрузки элементов можно использовать ObjectOutputStream и ObjectInputStream.

Готовая реализация SavedList должна проходить все тесты из набора SavedListTest.