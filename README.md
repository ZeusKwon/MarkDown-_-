# MarkDown 

- 정보
아래 사이트들은 Markdown을 실시간으로 사용해볼 수 있는 온라인 서비스입니다.

[Dillinger](https://dillinger.io/)

[Stackedit](https://stackedit.io/app)

하나씩 배울 때마다 직접 연습해 보세요.

# **제목**

**`#`**를 사용하여 단계별로 제목을 표현할 수 있습니다.

**`#`**을 하나만 쓰면 1단계 제목이고, **`#`** 을 4개 사용하면 4단계 제목이 됩니다. 단계가 높아질수록 글자 크기가 작아집니다.

```
# 이것은 1단계 제목입니다.
## 이것은 2단계 제목입니다.
### 이것은 3단계 제목입니다.
#### 이것은 4단계 제목입니다.

이것은 일반 글입니다.

```

# **이것은 1단계 제목입니다.**

## **이것은 2단계 제목입니다.**

### **이것은 3단계 제목입니다.**

### **이것은 4단계 제목입니다.**

이것은 일반 글입니다.

# **번호가 있는 목록**

아래처럼 적으면 번호가 있는 목록(리스트)을 만들 수 있습니다.

```
1. 첫 번째 할일입니다.
2. 두 번째 할일입니다.
3. 세 번째 할일입니다.

```

1. 첫 번째 할일입니다.
2. 두 번째 할일입니다.
3. 세 번째 할일입니다.

# **번호가 없는 목록**

숫자 대신 **`*`**을 사용하면, 번호가 없는 목록을 만들 수도 있습니다.

```
* 번호가 없는 목록입니다.
* 번호가 없는 목록입니다.
* 번호가 없는 목록입니다.

```

- 번호가 없는 목록입니다.
- 번호가 없는 목록입니다.
- 번호가 없는 목록입니다.

# **줄 바꿈**

아래와 같이 입력해 봅시다.

```
경찰청 철창살은 외철창살이냐 쌍철창살이냐?
내가 그린 기린 그림은 잘 그린 기린 그림이고 네가 그린 기린 그림은 잘 못 그린 기린 그림이다.
신인 샹송 가수의 신춘 샹송 쇼.

```

경찰청 철창살은 외철창살이냐 쌍철창살이냐?내가 그린 기린 그림은 잘 그린 기린 그림이고 네가 그린 기린 그림은 잘 못 그린 기린 그림이다.신인 샹송 가수의 신춘 샹송 쇼.

그런데 실행된 값을 보면 줄 바꿈이 안 되어 있죠? 줄 바꾸기를 하려면 문장의 맨 끝에 **`Space`** 키를 두 번 눌러야 합니다.

```
경찰청 철창살은 외철창살이냐 쌍철창살이냐?vv
내가 그린 기린 그림은 잘 그린 기린 그림이고 네가 그린 기린 그림은 잘 못 그린 기린 그림이다.vv
신인 샹송 가수의 신춘 샹송 쇼.

```

경찰청 철창살은 외철창살이냐 쌍철창살이냐?  
내가 그린 기린 그림은 잘 그린 기린 그림이고 네가 그린 기린 그림은 잘 못 그린 기린 그림이다.  
신인 샹송 가수의 신춘 샹송 쇼.

# **문단 바꿈**

문단을 바꾸는 효과를 위해서는 **`Enter`** 키를 두 번 눌러 주세요.

```
경찰청 철창살은 외철창살이냐 쌍철창살이냐?

내가 그린 기린 그림은 잘 그린 기린 그림이고 네가 그린 기린 그림은 잘 못 그린 기린 그림이다.

신인 샹송 가수의 신춘 샹송 쇼.

```

경찰청 철창살은 외철창살이냐 쌍철창살이냐?

내가 그린 기린 그림은 잘 그린 기린 그림이고 네가 그린 기린 그림은 잘 못 그린 기린 그림이다.

신인 샹송 가수의 신춘 샹송 쇼.

# **문자 강조**

- **``**와 **`_`**를 사용하면 글자를 꾸밀 수 있습니다.

```
이탈릭체는 *별표*나 _언더바_로.

볼드체는 **별표 두 개**나 __언더바 두 개__로.

**별표와 _언더바_**를 섞어서.

취소선은 ~~물결~~로.

```

이탈릭체는 *별표*나 *언더바*로.

볼드체는 **별표 두 개**나 **언더바 두 개**로.

**별표와 *언더바***를 섞어서.

취소선은 ~~물결~~로.

# **링크**

어떤 사이트로의 링크를 걸 수도 있습니다.

```
코딩 강의는 역시 [코드잇](https://www.codeit.kr)이죠!

```

코딩 강의는 역시 [코드잇](https://www.codeit.kr/)이죠!

# **이미지**

이미지를 추가할 수도 있습니다.

```
![코드잇](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)

```

![https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg]https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)

# **코드 블록**

` 세 개로 “코드 블록”을 추가해 보세요. 언어도 지정해 줄 수 있습니다!

```
```python
print('hello world!')
for i in range(10):
    print(i)
```

```

```
print('hello world!')
for i in range(10):
    print(i)

```

# **인라인 코드**

``로 코드를 감싸면 “인라인 코드”를 쓸 수 있습니다.

```
값을 출력하고 싶으면 `print` 함수를 사용하면 되겠죠?

```

값을 출력하고 싶으면 **`print`** 함수를 사용하면 되겠죠?

# **구분선**

- **`--`**으로 구분선을 추가할 수 있습니다.

```
구분 선 위

---

구분 선 아래

```

구분 선 위

---

구분 선 아래
