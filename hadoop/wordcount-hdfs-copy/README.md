# Building and running

    $ hadoop dfs -rmr /user/gutenberg/output
    $ cd hadoop/wordcount-hdfs-copy
    $ mvn clean package appassembler:assemble
    $ sh ./target/appassembler/bin/wordcount

