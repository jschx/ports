$OpenBSD$

COMMENT =		most readable font for programming, x11 version

DISTNAME =		profont-x11
PKGNAME =		profont-x11-1.0
CATEGORIES =		fonts x11

HOMEPAGE =		http://www.tobiasjung.name/profont/

MAINTAINER =		Joe Schillinger <me@schil.li>

# redistribute unmodified copies with included license
PERMIT_PACKAGE_CDROM =		Yes

MASTER_SITES =		http://www.tobiasjung.name/downloadfile.php/?file=
EXTRACT_SUFX =		.zip

NO_BUILD=		Yes
NO_TEST =		Yes

FONTDIR =		${PREFIX}/share/fonts/${DISTNAME}

do-install:
	${INSTALL_DATA_DIR} ${FONTDIR}
	${INSTALL_DATA} ${WRKDIR}/${DISTNAME}/*.pcf ${FONTDIR}
	${INSTALL_DATA} ${WRKDIR}/${DISTNAME}/LICENSE \
		${FONTDIR}/LICENSE

.include <bsd.port.mk>
