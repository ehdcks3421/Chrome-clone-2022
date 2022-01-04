# Chrome clone

background.js, quotes.js

- Math.random을 사용하여 random 인덱스를 생성하여 무작위로 background와 quotes를 생성

clock.js

- new Date() 객체를 사용하여 날짜, 시간 출력
- setInterval(getClock, 1000)을 사용하여 1초마다 시간 갱신

greetings.js

- submit 이벤트가 발생한다면 localstorage에 유저값 저장
- 저장을 했다면 greeting message hidden

todo.js

- 유저로부터 submit된 value를 localstorage에 string화한 객체(id와 todo)배열로 저장

weather.js

- openweathermap API를 사용하여 실시간 사용자 위치와 날씨 return
