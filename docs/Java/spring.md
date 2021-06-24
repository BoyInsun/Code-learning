# @SpringBootApplication 注解

@SpringBootApplication 注解包含三个主要的注解

* @SpringBootConfiguration

  @SpringBootConfiguration 跟进去发现，就等价于@Configuration,一个是SpringBoot 中的名称，一个是Spring 的名称。@Configuration 本质上也就是一个 @Component ,也是一个组件而已。

* @EnableAutoConfiguration

  打开SpringBoot 的自动配置机制

* @ComponentScan

​      允许程序自动扫描包，扫描当前包及其子包下标注了 @Component 、@Controller、@Service、@Repository 类并纳入到 Spring 容器中进行管理