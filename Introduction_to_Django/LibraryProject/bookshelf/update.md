```python
from bookshelf.models import Book
book = Book.objects.get(id=1)
book.title = "Animal Farm"
book.save()