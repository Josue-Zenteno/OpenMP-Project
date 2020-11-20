# Authors: - Josue Carlos Zenteno Yave
#		   - Sergio Silvestre
 
all: OrdenaVector.c OrdenaVectorOMP.c
	gcc OrdenaVector.c -o OrdenaVector -fopenmp
	gcc OrdenaVectorOMP.c -o OrdenaVectorOMP -fopenmp

debug_seq:
	gcc OrdenaVector.c -g -fopenmp
debug_par:
	gcc OrdenaVectorOMP.c -g -fopenmp
clean:
	$(RM) OrdenaVector
	$(RM) OrdenaVectorOMP