To compile:

cd <root>/com/brendteneickstaedt/csc552/project
javac *.classes

To run:

NOTE: Run each of the following in a separate terminal/process, in this order. This allows you to simulate a distributed system.

cd <root>/com/brendteneickstaedt/csc552/project
java StartSlave 55556

cd <root>/com/brendteneickstaedt/csc552/project
java StartSlave 55557

cd <root>/com/brendteneickstaedt/csc552/project
java StartSlave 55558

cd <root>/com/brendteneickstaedt/csc552/project
java StartMaster 55555 55556 55557 55558

cd <root>/com/brendteneickstaedt/csc552/project
java PlayerSim
