<h2>Defines arguments and environmnets at build stage and run stage<h2>

<h4>Defining arguments at image build stage<h4>

For defineing arguments at build stage, by default: Test
<pre> docker image build -t "IMAGE-NAME" --build-arg "arg" .</pre>

<h4>Defining environmnet at container run <h4>

For defineing environmnet at container run, by default: Test
<pre> docker container run -it -e NAME="name" "IMAGE-NAME"</pre>

