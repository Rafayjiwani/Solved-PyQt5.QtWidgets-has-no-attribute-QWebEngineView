# Solved PyQt5.QtWidgets has no attribute QWebEngineView
Solved AttributeError: module 'PyQt5.QtWidgets' has no attribute 'QWebEngineView'

If you've encountered the error "module 'PyQt5.QtWidgets' has no attribute 'QWebEngineView'" in your PyQt5 project, fear not! Follow these simple steps to resolve the issue:

**Step 1: Install PyQtWebEngine**

First things first, ensure you have PyQtWebEngine installed. You can do this easily via pip:

```
pip install PyQtWebEngine
```

This command will fetch and install the necessary PyQtWebEngine package for your project.

**Step 2: Import Correctly**

Now that you have PyQtWebEngine installed, make sure to import the `QWebEngineView` class correctly in your Python script. Instead of:

```python
from PyQt5.QtWidgets import QWebEngineView
```

Use:

```python
from PyQt5.QtWebEngineWidgets import QWebEngineView
```

This adjusted import statement ensures that you're referencing the correct module containing the `QWebEngineView` class, resolving the attribute error.

By following these two simple steps, you'll be back on track with your PyQt5 project, enjoying the full functionality of the `QWebEngineView` class without any errors. Happy coding!
