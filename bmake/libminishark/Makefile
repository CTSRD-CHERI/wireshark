.include "Makefile.src"

LIB=	minishark

CFLAGS+=	-DMINISHARK \
		-DSANE_LEX \
		-I${.CURDIR}/..

.PATH: ${.CURDIR}

.include <bsd.own.mk>

.include <bsd.lib.mk>
