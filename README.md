# hello-world


public class HelloWorldController {
    @RequestMapping("/hello")
    public String index() {
        return "Hello World";
    }
}
