# Created by: arved
# $FreeBSD$

PORTNAME=	Graph-ReadWrite
PORTVERSION=	2.09
CATEGORIES=	graphics perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	perl@FreeBSD.org
COMMENT=	Reading and Writing a variety of graph file formats

LICENSE=	ART10 GPLv1+
LICENSE_COMB=	dual

BUILD_DEPENDS=	${RUN_DEPENDS}
RUN_DEPENDS=	p5-Graph>=0.50:math/p5-Graph \
		p5-Parse-Yapp>=0:devel/p5-Parse-Yapp \
		p5-XML-Parser>=0:textproc/p5-XML-Parser \
		p5-XML-Writer>=0:textproc/p5-XML-Writer

NO_ARCH=	yes
USES=		perl5
USE_PERL5=	configure

.include <bsd.port.mk>
