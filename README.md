# list-stopword-sastrawi-python
## List stopword tersebut merupakan implementasi dari penggunaan library Sastrawi. contohnya dapat dilihat pada kode barikut:

```python
from Sastrawi.StopWordRemover.StopWordRemoverFactory import StopWordRemoverFactory, StopWordRemover, ArrayDictionary
stop_factory = StopWordRemoverFactory().get_stop_words()
print(stop_factory)
```
