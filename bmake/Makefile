LIBDIRS=	libairpdcap \
		libminitap \
		libminishark \
		libui \
		libwiretap \
		libwireshark \
		libwsutil \
		libwmem
PROGDIRS=	minishark \
		tshark

TGTS=	all clean depend obj

${TGTS}:
.for _DIR in ${LIBDIRS} ${PROGDIRS}
	${MAKE} -C ${_DIR} ${.TARGET}
.endfor

.include <bsd.subdir.mk>
