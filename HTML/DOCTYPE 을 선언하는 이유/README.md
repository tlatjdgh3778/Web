html 문서의 제일 위에 보면 `<!DOCTYPE html>` 이라는 코드를 볼 수 있는데, 이게 무엇이고 왜 사용하는지 알아보자.

`<!DOCTYPE html>` 을 DTD(Document Type Definition)이라고도 한다. 
> 컴퓨터 용어로, SGML 계열의 마크업 언어에서 문서 형식을 정의하는 것이다. SGML을 비롯해 HTML, XHTML, XML 등에서 쓰인다.

DOCTYPE은 간단히 말하면 어떠한 문서 형식을 따르고 있다는 것을 알려주는 역할을 한다.

HTML5의 경우에는 SGML에 기반을 두지 않아서 DTD 참조가 필요없지만 이전 버전의 HTML은 SGML에 기반을 두어 만들어졌기 때문에 DTD 참조가 필요하다. 때문에 DOCTYPE 선언을 할 때 뒤에 DTD 참조 URL이 들어간다.

* HTML5
```
<!DOCTYPE html>
```

* HTML 4.01 Strict
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

* XHTML 1.1
```
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
```

현재 웹 표준이 HTML5로 정의되어 있기 때문에 웹 문서를 작성할 때에는 `<!DOCTYPE html>` 을 적어주면 된다.
