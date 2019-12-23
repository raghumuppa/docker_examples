<h2>Defines arguments and environmnets at build stage and run stage</h2>

<h5>Defining arguments at image build stage</h5>

For defineing arguments at build stage, by default: Test
<pre> docker image build -t "IMAGE-NAME" --build-arg "arg" .</pre>

<h5>Defining environmnets at container run</h5>

For defineing environmnet at container run, by default: Test
<pre> docker container run -it -e NAME="name" "IMAGE-NAME"</pre>

