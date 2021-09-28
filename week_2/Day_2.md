I have no idea how to format my code blocks


## very proud of googling this one correctly
```javascript
const recursiveAsk = (questionsArr, iter = 0, ansArr = []) => {
  rl.question(questionsArr[0], (answer) => {
    console.log(`Your Answer: ${answer}`);
    ansArr.push(answer);
    
    if (iter === questionsArr.length - 1) {
      for (let ans of ansArr) {
        console.log(ans);
      }
      return rl.close();
    }
    recursiveAsk(questionsArr.slice(1), iter++, ansArr);
  });
};
```
It's fine here, but terrible in slack.

Async functions can't return data?

You have to make sure they come back, then async get their data afterwards