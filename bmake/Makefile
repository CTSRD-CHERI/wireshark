LIBDIRS=	libairpdcap \
		libminitap \
		libminishark \
		libui \
		libwsutil \
		libwmem
PROGDIRS=	dumpcap \
		minishark

#		libwiretap \
#		libwireshark \
#		tshark

TGTS=	all clean depend obj

${TGTS}:
.for _DIR in ${LIBDIRS} ${PROGDIRS}
	${MAKE} -C ${_DIR} ${.TARGET}
.endfor

.include <bsd.subdir.mk>
