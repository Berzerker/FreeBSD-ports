# $FreeBSD$

PORTNAME=	later
PORTVERSION=	0.7.5
PORTREVISION=	1
CATEGORIES=	devel
DISTNAME=	${PORTNAME}_${PORTVERSION}

MAINTAINER=	tota@FreeBSD.org
COMMENT=	Utilities for Delaying Function Execution

LICENSE=	GPLv2+

BROKEN_i386=	Undefined symbol "_ZN5boost7atomics6detail8lockpool11scoped_lockC1EPVKv"

USES=		cran:auto-plist,compiles

CRAN_DEPENDS=	R-cran-Rcpp>=0.12.9:devel/R-cran-Rcpp \
		R-cran-rlang>0:devel/R-cran-rlang \
		R-cran-BH>0:devel/R-cran-BH
BUILD_DEPENDS=	${CRAN_DEPENDS}
RUN_DEPENDS=	${CRAN_DEPENDS}

.include <bsd.port.mk>
