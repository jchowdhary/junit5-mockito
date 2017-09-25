# junit5-mockito
Simple usage on how to use Mockito with Junit5

We need to harness the JUNIT5 main feature @ExtendWith.
We will be creating a new class MockitoExtension.java which will implement 
- ParameterResolver
- TestInstancePostProcessor

All other junit classes will include the annotation
 - @ExtendWith(MockitoExtension.class) to execute the junit test methods.
 
 
