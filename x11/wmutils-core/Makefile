COMMENT =	set of window manipulation tools

V =	1.2

DISTNAME =	${GH_ACCOUNT}-${GH_PROJECT}-${V}

GH_ACCOUNT =	wmutils
GH_PROJECT =	core
GH_TAGNAME =	v${V}

CATEGORIES =	x11

HOMEPAGE =	https://github.com/wmutils

MAINTAINER =	Joe Schillinger <me@schil.li>

# ISC
PERMIT_PACKAGE_CDROM =	Yes

WRKDIST =	${WRKOBJDIR}/${DISTNAME}/${GH_PROJECT}-${GH_TAGNAME:S/v//g}
#WRKDIST =	${WRKOBJDIR}/${DISTNAME}/${GH_PROJECT}-${GH_COMMIT}

WANTLIB =	c xcb

.include <bsd.port.mk>
