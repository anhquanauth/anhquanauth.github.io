class Person:
    def __init__(self, name, hometown):
        self.name = name
        self.hometown = hometown
    
    def introduce(self):
        print(f"Xin chào! Tôi là {self.name}, quê quán ở {self.hometown}.")

# Sử dụng đối tượng để giới thiệu
me = Person("Nguyễn Quốc Anh Quân", "Hà Nội")
me.introduce()
