CC = cc
CFLAGS = -Wall -Wextra -Werror -I$(HEADER)

NAME = libft.a
SRCS = ./srcs/ft_putchar.c \
	./srcs/ft_putstr.c \
	./srcs/ft_strcmp.c \
	./srcs/ft_strlen.c \
	./srcs/ft_swap.c \
OBJS = $(SRCS:.c=.o)
HEADER = ./includes

all: $(NAME)

$(NAME): $(OBJS)
	ar rcs $(NAME) $(OBJS)

clean:
	rm -rf  $(OBJS)

fclean: clean
	rm -f $(NAME)

re: fclean all
