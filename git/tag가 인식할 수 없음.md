tag가 인식할 수 없다고

## Liquid Exception: Liquid syntax error (line 232): Unknown tag 'block' in /home/runner/work/AI-chemist97.github.io/AI-chemist97.github.io/\_posts/2025-07-28-[FlickTalk]환경 세팅 2.md

Jekyll 4.4.1 Please append `--trace` to the `build` command
for any additional information or backtrace.

---

이런식으로 계속 뜨는데 해당 문제는 block 내에 {% 단어 %} 형태의 코드가 있을 때 해당 코드를 liquid 문법으로 처리하려는 과정에서 발생하려는 오류로 해당 코드 블럭을 통째로 liquid 문법으로 하지말라는 문법인
{% raw %}
{% endraw %}
로 감싸주면 된다

코드 블럭의 경우 저 사이에 ```html

```
이것도 넣어주면 된다.
```
