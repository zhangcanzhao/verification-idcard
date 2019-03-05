# verification-idcard
###### npm install --save-dev verificationid
###### 针对日期、省市、加权因子等三方面进行验证，但也不能绝对保证通过验证的身份证是正确的一定有持有该身份证的人存在。
```javascript
import idCard from 'verificationid'
console.log(idCard('41038*********4555'))
//返回true或false
```
