# ppmasmicrosvjava

### 3 Sample REST Service
RestController - Resource - returns domain object

```
@Controller
@ResponseBody
```


```
@ReauestMapping  //Maps the URI to controller class/method
```

```
@RequestParam(value="base") String a
```

##### Spring REST: App Execution
@SpringBootApplication
- @EnableAutoConfiguration: Spring Boot is to start adding beans based on classpath settings, other beans, and various property setting.
- @EnableWebMvc: Makes Web application by activating key behaviors such as setting up a DispatcherServlet
- @ComponentScan:Scan for other components, configurations, and services in the given package
