FROM gcr.io/oss-fuzz-base/base-builder-jvm

RUN apt-get update 
#&& apt-get install -y maven

COPY . jsyn
#RUN rm -rf javaparser/mayhem
#COPY mayhem/build.sh $SRC/

#COPY mayhem/*.java $SRC/

WORKDIR $SRC/jsyn

#ENV FUZZING_LANGUAGE=jvm SANITIZER=address FUZZING_ENGINE=libfuzzer
#RUN compile
#RUN chmod +x /out/jazzer_driver
