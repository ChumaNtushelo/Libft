# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: cntushel <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/05/20 09:46:35 by cntushel          #+#    #+#              #
#    Updated: 2019/07/05 14:42:21 by cntushel         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME		= libft.a

SRCS		= ft_strlen.c \
				ft_strcmp.c \
				ft_bzero.c \
			  	*ft_strdup.c \
			  	*ft_memset.c \
			  	*ft_strcpy.c \
			  	*ft_strncpy.c \
				ft_strncmp.c \
			  	ft_tolower.c \
			  	ft_toupper.c \
				ft_isdigit.c \
				ft_isalpha.c \
				ft_isalnum.c \
				ft_isprint.c \
				ft_strcat.c \
				ft_isascii.c \
				ft_atoi.c \
				ft_strlcat.c \
				ft_memcpy.c \
				*ft_memccpy.c \
				*ft_memmove.c \
				*ft_memchr.c \
				ft_memcmp.c \
				*ft_strncat.c \
				*ft_strchr.c \
				*ft_strrchr.c \
				*ft_strstr.c \
				*ft_strnstr.c \
				ft_putchar.c \
				ft_putstr.c \
				ft_strdel.c \
				*ft_memalloc.c \
				ft_putchar_fd.c \
				ft_putstr_fd.c \
				ft_memdel.c \
				ft_striter.c \
				ft_striteri.c \
				ft_putendl.c \
				*ft_strmap.c \
				*ft_strmapi.c \
				*ft_strsub.c \
				ft_putendl_fd.c \
				ft_strclr.c \
				*ft_strnew.c \
				*ft_strjoin.c \
				ft_strequ.c \
				ft_strnequ.c \
				ft_putnbr.c \
				ft_putnbr_fd.c \
				*ft_strtrim.c \
				**ft_strsplit.c \
				*ft_itoa.c

OBJ			= ft_strlen.o \
			  ft_strcmp.o \
			  ft_bzero.o \
			  *ft_strdup.o \
			  *ft_memset.o \
			  *ft_strcpy.o \
			  *ft_strncpy.o \
			  ft_strncmp.o \
			  ft_tolower.o \
			  ft_toupper.o \
			  ft_isdigit.o \
			  ft_isalpha.o \
			  ft_isalnum.o \
			  ft_atoi.o \
			  ft_isascii.o \
			  ft_isprint.o \
			  ft_strcat.o \
			  ft_strlcat.o \
			  ft_memcpy.o \
			  *ft_memccpy.o \
			  *ft_memmove.o \
			  *ft_memchr.o \
			  ft_memcmp.o \
			  *ft_strncat.o \
			  *ft_strchr.o \
			  *ft_strrchr.o \
			  *ft_strstr.o \
			  *ft_strnstr.o \
			  ft_putchar.o \
			  ft_putstr.o \
			  ft_strdel.o \
			  *ft_memalloc.o \
			  ft_putchar_fd.o \
			  ft_putstr_fd.o \
			  ft_memdel.o \
			  ft_striter.o \
			  ft_striteri.o \
			  ft_putendl.o \
			  *ft_strmap.o \
			  *ft_strmapi.o \
			  *ft_strsub.o \
			  ft_putendl_fd.o \
			  ft_strclr.o \
			  *ft_strnew.o \
			  *ft_strjoin.o \
			  ft_strequ.o \
			  ft_strnequ.o \
			  ft_putnbr.o \
			  ft_putnbr_fd.o \
			  *ft_strtrim.o \
			  **ft_strsplit.o \
			  *ft_itoa.o

HEADERS		= includes

CC			= gcc

cflags		= -Wall -Wextra -Werror

all : $(NAME)

$(NAME):
	gcc -c $(cflags) $(SRCS)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

clean:
	/bin/rm -f $(OBJ)

fclean: clean
	/bin/rm -f $(NAME) $(OBJ)

re: fclean all
	gcc -c $(cflags) $(SRCS)
