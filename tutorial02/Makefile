all:
	make clean
	ghc ./Main.hs -o Main

clean:
	@if [ -f ./Main ];\
		then\
		rm ./Main 2> /dev/null;\
	else\
		echo "./Main already clean";\
	fi
