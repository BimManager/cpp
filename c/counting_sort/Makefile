# exam Makefile

CC := gcc
CFLAGS := -Wall -Wextra -Werror -g -I../../libft/include -L../../libft -lft

SRCS := counting_sort.c
NAME := a.out

all : $(NAME)

$(NAME) : $(SRCS)
	$(CC) $(CFLAGS) $^ -o $@

clean :
	rm -rf $(NAME)

re : clean all

.PHONY : all clean re


