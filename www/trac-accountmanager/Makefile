# $FreeBSD$

PORTNAME=	accountmanager
PORTVERSION=	0.5.${REV}
PORTREVISION=	2
PORTEPOCH=	1
CATEGORIES=	www devel python
MASTER_SITES=	LOCAL/kuriyama \
		http://trac-hacks.org/changeset/${REV}/accountmanagerplugin/trunk?old_path=/&format=zip&filename=
PKGNAMEPREFIX=	trac-
DIST_SUBDIR=	trac

MAINTAINER=	kuriyama@FreeBSD.org
COMMENT=	Account Manager Plugin for trac

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYING

RUN_DEPENDS=	tracd:www/trac

FETCH_BEFORE_ARGS=	-o ${DISTFILES}
REV=			12583
USES=			python:2.7 zip
USE_PYTHON=		distutils autoplist
WRKSRC=			${WRKDIR}/accountmanagerplugin/trunk
NO_ARCH=		yes

# --- trac.ini
# [components]
# acct_mgr.* = enabled
#
# [account-manager]
# password_format = htpasswd
# password_file = /var/trac/trac.htpasswd
#
# --- httpd.conf
# SetEnv PYTHON_EGG_CACHE "/tmp/cache"

.include <bsd.port.mk>
