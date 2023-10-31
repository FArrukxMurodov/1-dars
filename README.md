# 1-dars
# 27-oktabr


# import sys
# from PyQt5.QtWidgets import QApplication, QWidget, QVBoxLayout, QLabel
#
# app = QApplication(sys.argv)
#
# window = QWidget()
# layout = QVBoxLayout()
# red_label = QLabel()
# red_label.setStyleSheet("background-color: red;")
#
# blue_label = QLabel()
# blue_label.setStyleSheet("background-color: blue;")
#
# layout.addWidget(red_label)
# layout.addWidget(blue_label)
# window.setLayout(layout)
#
# window.show()
# sys.exit(app.exec_())










#
#
# import sys
# from PyQt5.QtWidgets import QApplication, QWidget, QLabel, QLineEdit, QPushButton, QVBoxLayout
# app = QApplication(sys.argv)
# window = QWidget()
# layout = QVBoxLayout()
#
# label_username = QLabel("Username:")
# lineedit_username = QLineEdit()
#
# label_password = QLabel("Password:")
# lineedit_password = QLineEdit()
# lineedit_password.setEchoMode(QLineEdit.Password)
#
# label_email = QLabel("Email:")
# lineedit_email = QLineEdit()
#
# label_confirm_password = QLabel("Confirm Password:")
# lineedit_confirm_password = QLineEdit()
# lineedit_confirm_password.setEchoMode(QLineEdit.Password)
#
# label_phone = QLabel("Phone:")
# lineedit_phone = QLineEdit()
#
# button_signup = QPushButton("Sign Up")
#
# layout.addWidget(label_username)
# layout.addWidget(lineedit_username)
#
# layout.addWidget(label_password)
# layout.addWidget(lineedit_password)
#
# layout.addWidget(label_email)
# layout.addWidget(lineedit_email)
#
# layout.addWidget(label_confirm_password)
# layout.addWidget(lineedit_confirm_password)
#
# layout.addWidget(label_phone)
# layout.addWidget(lineedit_phone)
#
# layout.addWidget(button_signup)
#
# window.setLayout(layout)
#
# window.show()
#
# sys.exit(app.exec_())


#
#
#
# import sys
# from PyQt5.QtWidgets import QApplication, QWidget, QLabel, QLineEdit, QPushButton, QVBoxLayout
#
# app = QApplication(sys.argv)
#
# window = QWidget()
#
# layout = QVBoxLayout()
#
# label_miles = QLabel("Distance in miles:")
# lineedit_miles = QLineEdit()
#
# button_convert = QPushButton("Convert")
# label_kilometers = QLabel("Distance in kilometers: 0")
#
# # Elementlarni layoutga qo'shish
# layout.addWidget(label_miles)
# layout.addWidget(lineedit_miles)
# layout.addWidget(button_convert)
# layout.addWidget(label_kilometers)
#
# def convert():
#     miles = float(lineedit_miles.text())
#     kilometers = miles * 1.60934
#     label_kilometers.setText(f"Distance in kilometers: {kilometers}")
#
# button_convert.clicked.connect(convert)
#
# window.setLayout(layout)
#
# window.show()
#
# sys.exit(app.exec_())










#
# import sys
# from PyQt5.QtWidgets import QApplication, QWidget, QVBoxLayout, QHBoxLayout, QLabel
# class MyWidget(QWidget):
#     def __init__(self):
#         super().__init__()
#
#         vertical_layout = QVBoxLayout()
#
#         red_label = QLabel()
#         red_label.setStyleSheet("background-color: red;")
#         vertical_layout.addWidget(red_label)
#
#         blue_label = QLabel()
#         blue_label.setStyleSheet("background-color: blue;")
#         vertical_layout.addWidget(blue_label)
#
#         horizontal_layout = QVBoxLayout()
#         black_label = QLabel()
#         black_label.setStyleSheet("background-color: black; color: white;")
#         horizontal_layout.addWidget(black_label)
#
#         green_label = QLabel()
#         green_label.setStyleSheet("background-color: green;")
#         horizontal_layout.addWidget(green_label)
#
#         yellow_label = QLabel()
#         yellow_label.setStyleSheet("background-color: yellow;")
#         horizontal_layout.addWidget(yellow_label)
#
#         main_layout = QHBoxLayout()
#         main_layout.addLayout(vertical_layout)
#         main_layout.addLayout(horizontal_layout)
#
#         self.setLayout(main_layout)
# if __name__ == '__main__':
#     app = QApplication(sys.argv)
#     widget = MyWidget()
#     widget.show()
#     sys.exit(app.exec_())




#
# import sys
# from PyQt5.QtWidgets import QApplication, QWidget, QVBoxLayout, QHBoxLayout, QLabel
# class MyWidget(QWidget):
#     def __init__(self):
#         super().__init__()
#
#         vertical_layout = QVBoxLayout()
#
#         yellow_label = QLabel()
#         yellow_label.setStyleSheet("background-color: yellow;")
#         vertical_layout.addWidget(yellow_label)
#
#         blue_label = QLabel()
#         blue_label.setStyleSheet("background-color: blue;")
#         vertical_layout.addWidget(blue_label)
#
#         purple_label = QLabel()
#         purple_label.setStyleSheet("background-color: purple;")
#         vertical_layout.addWidget(purple_label)
#
#         horizontal_layout = QHBoxLayout()
#
#         green_label = QLabel()
#         green_label.setStyleSheet("background-color: green;")
#         horizontal_layout.addWidget(green_label)
#
#         yellow_label = QLabel()
#         yellow_label.setStyleSheet("background-color: yellow;")
#         horizontal_layout.addWidget(yellow_label)
#
#         main_layout = QVBoxLayout()
#         main_layout.addLayout(vertical_layout)
#         main_layout.addLayout(horizontal_layout)
#         self.setLayout(main_layout)
#
# if __name__ == '__main__':
#     app = QApplication(sys.argv)
#     widget = MyWidget()
#     widget.show()
#     sys.exit(app.exec_())

#
# import sys
# from PyQt5.QtWidgets import QApplication, QWidget, QVBoxLayout, QHBoxLayout, QLabel
# class Example(QWidget):
#     def __init__(self):
#         super().__init__()
#         self.initUI()
#     def initUI(self):
#         vbox = QVBoxLayout()
#
#         red_label = QLabel('To\'qsariq')
#         red_label.setStyleSheet('background-color: red;')
#         vbox.addWidget(red_label)
#
#         blue_label = QLabel('Ko\'k')
#         blue_label.setStyleSheet('background-color: blue;')
#         vbox.addWidget(blue_label)
#
#         green_label = QLabel('Jigarrang')
#         green_label.setStyleSheet('background-color: green;')
#         vbox.addWidget(green_label)
#
#         hbox = QHBoxLayout()
#
#         green_widget = QLabel('Yashil')
#         green_widget.setStyleSheet('background-color: green;')
#         hbox.addWidget(green_widget)
#
#         yellow_widget = QLabel('Sariq')
#         yellow_widget.setStyleSheet('background-color: yellow;')
#         hbox.addWidget(yellow_widget)
#
#         orange_widget = QLabel('Jigarrang')
#         orange_widget.setStyleSheet('background-color: orange;')
#         hbox.addWidget(orange_widget)
#
#         pink_widget = QLabel('Havorang')
#         pink_widget.setStyleSheet('background-color: pink;')
#         hbox.addWidget(pink_widget)
#
#         white_label = QLabel('Pasiga pushti')
#         white_label.setStyleSheet('background-color: white;')
#         vbox.addWidget(white_label)
#
#
#         purple_label = QLabel('Alvonrang')
#         purple_label.setStyleSheet('background-color: purple;')
#         vbox.addWidget(purple_label)
#
#
#         green_red_label = QLabel('Yashil qizil')
#         green_red_label.setStyleSheet('background-color: green; color: red;')
#         vbox.addWidget(green_red_label)
#
#         yellow_label = QLabel('Sariq')
#         yellow_label.setStyleSheet('background-color: yellow;')
#         vbox.addWidget(yellow_label)
#
#         vbox.addLayout(hbox)
#
#         self.setLayout(vbox)
#
#         self.setGeometry(100, 100, 300, 300)
#         self.setWindowTitle('PyQt5 Layoutlar')
#         self.show()
#
#
# if __name__ == '__main__':
#     app = QApplication(sys.argv)
#     ex = Example()
#     sys.exit(app.exec_())
#


import sys
from PyQt5.QtWidgets import QApplication, QWidget, QHBoxLayout, QVBoxLayout, QLabel


class Example(QWidget):
    def __init__(self):
        super().__init__()
        self.initUI()
    def initUI(self):
        # Asosiy layout
        main_layout = QVBoxLayout()

        hbox1 = QHBoxLayout()

        green_widget = QLabel('Yashil')
        green_widget.setStyleSheet('background-color: green;')
        hbox1.addWidget(green_widget)

        yellow_widget = QLabel('Sariq')
        yellow_widget.setStyleSheet('background-color: yellow;')
        hbox1.addWidget(yellow_widget)

        orange_widget = QLabel('Jigarrang')
        orange_widget.setStyleSheet('background-color: orange;')
        hbox1.addWidget(orange_widget)

        pink_widget = QLabel('Havorang')
        pink_widget.setStyleSheet('background-color: pink;')
        hbox1.addWidget(pink_widget)

        main_layout.addLayout(hbox1)

        hbox2 = QHBoxLayout()

        red_widget = QLabel('Qizil')
        red_widget.setStyleSheet('background-color: red;')
        hbox2.addWidget(red_widget)

        purple_widget = QLabel('Pushti')
        purple_widget.setStyleSheet('background-color: purple;')
        hbox2.addWidget(purple_widget)

        main_layout.addLayout(hbox2)

        hbox3 = QHBoxLayout()

        green_red_widget = QLabel('Yashil Qizil')
        green_red_widget.setStyleSheet('background-color: green; color: red;')
        hbox3.addWidget(green_red_widget)

        yellow_red_widget = QLabel('Sariq Qizil')
        yellow_red_widget.setStyleSheet('background-color: yellow; color: red;')
        hbox3.addWidget(yellow_red_widget)

        orange_red_widget = QLabel('Jigarrang Qizil')
        orange_red_widget.setStyleSheet('background-color: orange; color: red;')
        hbox3.addWidget(orange_red_widget)

        main_layout.addLayout(hbox3)

        self.setLayout(main_layout)

        self.setGeometry(100, 100, 300, 200)
        self.setWindowTitle('PyQt5 Layoutlar')
        self.show()

if __name__ == '__main__':
    app = QApplication(sys.argv)
    ex = Example()
    sys.exit(app.exec_())

