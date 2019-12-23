<h2>Defines arguments and environmnets at build stage and run stage<h2>

Defining arguments at image build stage

For defineing arguments at build stage, by default: Test
<pre> docker image build -t "IMAGE-NAME" --build-arg "arg" .</pre>

Defining environmnets at container run

For defineing environmnet at container run, by default: Test
<pre> docker container run -it -e NAME="name" "IMAGE-NAME"</pre>

