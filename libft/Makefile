NAME = libft.a

FILEC = ft_*.c

FILEO = *.o

LIB = libft.h

FLAG = -Wall -Wextra -Werror

all: $(NAME)

$(NAME): 
	gcc $(FLAG) -c $(FILEC) -I $(LIB)
	ar rc $(NAME) $(FILEO)
	ranlib $(NAME)

clean:
	rm -rf $(FILEO)

fclean: clean
	rm -rf $(NAME)

re: fclean all 