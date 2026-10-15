## 요구사항

## 클래스 다이어그램



## 시퀀스 다이어그램

## Service 간 의존 방향

MessageService → ChannelService → UserService

       └──────────────────────────↗
       
```mermaid
flowchart TD
    MS[MessageService<br/>메시지 생성·수정·삭제] --> CS[ChannelService<br/>멤버십·소유권 관리]
    CS --> US[UserService<br/>사용자 관리]
    MS --> US
```
