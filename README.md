# Pytorch Fizz Buzz

This implementation is based on the (very fun) post by Joel Gruss. Fizz Buzz is a traditional
programming interview question where the interviewee is asked to write a program that behaves
as the following function:

```
    fizzbuzz(x) ->
    	| 'fizzbuzz' if x % 15 == 0
    	| 'fizz' if x % 3 == 0
    	| 'buzz' if x % 5 == 0
    	| str(x) otherwise
```

Instead, Gruss took the challenge to the next level by writing a Tensorflow Multilayer
Perceptron that predicts which class a binary pattern corresponds to. Since the implementation
is very straighforward and I'm learning PyTorch, I decided to give it a try.

