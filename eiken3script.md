# 英検準2級二次試験スクリプトと会話表現

## 入室~着席

```mermaid
sequenceDiagram
    participant M as 面接官
    participant J as 受験生
    rect rgb(255,250,205)
    Note right of M: 挨拶
    M->>J: Hello.  
    J-->>M: Hello.
    end
    rect rgb(255,250,205)
    Note right of M: 面接カードを渡す
    M->>J: Can I have your card, please?
    J-->>M: Yes.Here you are.
    M->>J: Thank you.
    end
    rect rgb(255,250,205)
    Note right of M: 着席
    M->>J: Please sit down.
    J-->>M: OK.Thanks.
    end
```

<div style="page-break-before:always"></div>

## 名前・級の確認~問題カードの受取

```mermaid
sequenceDiagram
    participant M as 面接官
    participant J as 受験生
    rect rgb(255,250,205)
    Note right of M: 氏名・級の確認・挨拶
    M->>J: Hello.
    J-->>M: Hello.
    M->>J: My name is [面接官の名前].What's your name, please?
    J-->>M: My name is [受験生の名前].
    M->>J: Mr./Ms. [受験生の名前],this is the Grade Pre-2 test, OK?
    J-->>M: Yes.
    M->>J: Mr./Ms.[受験生の名前], How are you today?
    J-->>M: I'm fine, thnak you.
    M->>J: Good.
    end
    rect rgb(255,250,205)
    Note right of M: 問題カードを受け取る
    M->>J: OK, let's start the test. Here's your card.
    J-->>M: Thank you.
    end
```

<div style="page-break-before:always"></div>

## 音読～黙読

```mermaid
sequenceDiagram
    participant M as 面接官
    participant J as 受験生
    rect rgb(255,250,205)
    Note right of M: 黙読
    M->>J: First, please read the passage silently for 20 seconds.
    end
    rect rgb(255,250,205)
    Note right of M: 音読
    M->>J: Now,please read it aloud.
    end
```

<div style="page-break-before:always"></div>

## 質問(No.1~No.3)

```mermaid
sequenceDiagram
    participant M as 面接官
    participant J as 受験生
    M->>J: Now, I'll ask you five questions.
    rect rgb(255,250,205)
    Note right of M: No.1 パッセージについての質問
    M->>J: Please look at the passage.
    M->>J: [問題No.1]
    J-->>M: [問題No.1の解答]
    end
    rect rgb(255,250,205)
    Note right of M: No.2 イラストについての質問
    M->>J: No2,[問題No.2]
    J-->>M: [問題No.2の解答]
    end
    rect rgb(255,250,205)
    Note right of M: No.3 イラストについての質問
    M->>J: No3,[問題No.3]
    J-->>M: [問題No.3の解答]
    end
```

<div style="page-break-before:always"></div>

## 質問(No.4~No.5)

```mermaid
sequenceDiagram
    participant M as 面接官
    participant J as 受験生
    rect rgb(255,250,205)
    Note right of M: 問題カードを裏返す
    M->>J: Now,Mr./Ms.[受験生の名前], please turn the card over.
    end
    rect rgb(255,250,205)
    Note right of M: No.4 受験生自身について問う問題
    M->>J: No4,[問題No.4]
    J-->>M: [問題No.4の解答]
    end
    rect rgb(255,250,205)
    Note right of M: No.5 受験生自身について問う問題
    M->>J: No.5,[問題No.5]
    J-->>M: [問題No.5の解答]
    end
```

<div style="page-break-before:always"></div>

## 面接カードを返す~退室

```mermaid
sequenceDiagram
    participant M as 面接官
    participant J as 受験生
    rect rgb(255,250,205)
    Note right of M: 問題カードを面接官に返す
    M->>J: Ok, Mr./Ms.[受験生の名前],this is the end of the test.
    M->>J: May I have your card back, please?
    J-->>M: Yes. Here you are.
    M->>J: Thank you.
    end
    rect rgb(255,250,205)
    Note right of M: 退室
    M->>J: You may go now. Good-bye.
    J-->>M: Bye.
    M->>J: Have a nice day.
    J-->M: Thanks.
    end
```

<div style="page-break-before:always"></div>

## 使える英語表現

### 聞き取れなかった時に聞き返す表現

- I beg your pardon?
- Pardon me?
- Pardon?
- Excuse me?
- Sorry, could you repeat the question?
- Could you repeat again?
- Would you say that again, please?
- What was that again?

Pardon?は **I beg your padon?** の略でめっちゃくちゃ丁寧な表現。  

### 考える時間がほしい時

- Well...
- Let's see.
- Let me see.
