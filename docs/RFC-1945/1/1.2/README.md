# 1.2 용어

https://datatracker.ietf.org/doc/html/rfc1945#section-1.2

<details>
<summary>원문</summary>

```
This specification uses a number of terms to refer to the roles
   played by participants in, and objects of, the HTTP communication.
```
</details>

HTTP에서 사용되는 다양한 용어들을 이 문서에서는 다음과 같이 사용됩니다.

<details>
<summary>원문</summary>

```text
   connection
       A transport layer virtual circuit established between two
       application programs for the purpose of communication.
```
</details>

#### connection 
응용 프로그램들 사이에 통신을 목적으로 전송 계층에서 가상 회선을 구축한 상태

<details>
<summary>원문</summary>

```text
   message
       The basic unit of HTTP communication, consisting of a structured
       sequence of octets matching the syntax defined in Section 4 and
       transmitted via the connection.
```
</details>

#### message
HTTP의 기본 통신 단위, Section 4에 정의된 형식에 맞추어 구조화된 8bit 데이터의 연속<br>
connection을 통해 전송된다.

<details>
<summary>원문</summary>

```text
   request
       An HTTP request message (as defined in Section 5).
```
</details>

#### request
HTTP 요청 message(Section 5에 정의됨)

<details>
<summary>원문</summary>

```text
   response
       An HTTP response message (as defined in Section 6).
```
</details>

#### response
HTTP 응답 message(Section 6에 정의됨)