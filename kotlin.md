
```
System Services
Example: System service on code
## Java
AlarmManager alarmManager = (AlarmManager) context.getSystemService(Context.ALARM_SERVICE);
NotificationManager notificationManager = (NotificationManager) context.getSystemService(Context.NOTIFICATION_SERVICE);

## Kotlin
val alarmManager = context.alarmManager()
val notificationManager = context.notificationManager()
```

```
Android getSystemService() 메소드->
http://promobile.tistory.com/169 참고
https://android-arsenal.com/details/1/1634 참고
```


**Kotlin 오픈소스 예제들** 
```markdown
https://github.com/yongjhih/kotlin-system-services
https://github.com/ttymsd/coordinator-behaviors/tree/master/example/src/main/kotlin/jp/bglb/bonboru/behaviors/app
```
