import matplotlib.pyplot as plt

# 연도와 결혼이주여성의 수
years = [2010, 2020]
marriage_immigrants = [187404, 296329]

plt.figure(figsize=(8, 6))
plt.plot(years, marriage_immigrants, marker='o', color='b', linestyle='-')

# 그래프 제목과 축 레이블
plt.title('결혼이주여성의 수 (2010년부터 2020년)')
plt.xlabel('연도')
plt.ylabel('결혼이주여성의 수')

# x 축 눈금 설정
plt.xticks(years)

# 그래프 표시
plt.grid(True)
plt.show()

