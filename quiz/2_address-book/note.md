# Promise (258page)

- 프로미스는 비동기 처리에 사용되는 객체
- new Promise()의 첫 번째 파라미터는 resolve고 두번째 파라미터는 reject
- 프로미스가 실행되었을 때 성공한 값은 resolve()에 넣고 실패한 값은 reject()에 넣음
- 성공한 값은 .then()의 콜백 함수에서 전달받고
- 실패한 값은 .catch()의 콜백 함수에서 전달 받음