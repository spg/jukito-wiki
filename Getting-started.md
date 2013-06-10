# Features
* DOC injection on test class fields and into test methods
* DOC and SUT reset before every test method call - new scope via @TestSingleton annotation
* installation of your custom Guice modules
* Environment Dependent Modules - one test, many environment configurations

# Configuration
* Put @RunWith(JukitoRunner.class) on test class
* Add inner class like  public static class A extends JukitoModule
 if you would like to install custom Guice modules or use @UseModules annotation

# Examples
* Ultra easy test - first shot - link
* @UseModules - link
* Installing custom modules - link
* Using methods factories to satisfy dependencies - link