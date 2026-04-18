# how-java-systems-work
core tech stuffs

### How to create beans manually in java systems with applicationContext.xml
```
ApplicationContext context = new ClassPathXmlApplicationContext("applicationBeanContext.xml");
		GreetingService gs =  (GreetingService) context.getBean("myBean");
		gs.sayHello();

```
