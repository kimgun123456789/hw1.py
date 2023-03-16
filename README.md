# hw1.py

https://colab.research.google.com/drive/1Bq1IPWM9iNAsbJqCKXJ0PNhdSi5hJb5O


def get_radius():
  r = int(input("넓이를 구하고자 하는 원의 반지름은?"))
  return r
def get_circle_area(r):
  return r*r*3.14
print()
r=get_radius()
s=get_circle_area(r)
print("반지름 ",r,"인 원의 넓이 = 3.14 x ",r," x ",r," = ",s)
