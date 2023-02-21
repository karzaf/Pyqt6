# Pyqt6

- install 
```
pip install PySide6
```

## basic program
```python
from PySide6.QtWidgets import QApplication, QWidget
import sys
#QApplication=main app library to use
app = QApplication(sys.argv)
window=QWidget()
window.show()
app.exec()
```

## set title program
```python
from PySide6.QtWidgets import QMainWindow
window = QMainWindow()
window.setWindowTitle("abc")
```

## set button Central
```python
from PySide6.QtWidgets import QPushButton
button = QPushButton()
button.setText("Press me")
window.setCentralWidget(button)
```
