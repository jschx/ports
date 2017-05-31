$OpenBSD$

COMMENT=		simple X screen locker

DISTNAME=		slock-1.3
REVISION=		1

CATEGORIES=		x11

HOMEPAGE=		http://tools.suckless.org/slock

MAINTAINER=		Joe Schillinger <me@schil.li>

# BSD
PERMIT_PACKAGE_CDROM=	Yes

WANTLIB=		X11 c Xext Xrandr

MASTER_SITES=		http://dl.suckless.org/tools/

MAKE_ENV=		CC="${CC}" \
			LDFLAGS="${LDFLAGS}"
FAKE_FLAGS=		DESTDIR=""

NO_TEST=		Yes

.include <bsd.port.mk>
