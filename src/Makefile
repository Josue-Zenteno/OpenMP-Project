# Authors: - Josue Carlos Zenteno Yave
#		   - Sergio Silvestre
 
all: OrdenaVector.c OrdenaVectorOMP.c
	gcc OrdenaVector.c -o OrdenaVector -fopenmp
	gcc OrdenaVectorOMP.c -o OrdenaVectorOMP -fopenmp

clean:
	$(RM) OrdenaVector
	$(RM) OrdenaVectorOMP