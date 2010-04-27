# New ports collection makefile for:	p5-Git-Wrapper
# Date created:				Apr 27th 2010
# Whom:	      				Otavio Fernandes <otaviof@gmail.com>
#
# $FreeBSD:$
#

PORTNAME=	Git-Wrapper
PORTVERSION=	0.008
CATEGORIES=	devel perl5
MASTER_SITES=	CPAN
MASTER_SITE_SUBDIR=	../by-authors/id/P/PE/PERIGRIN
PKGNAMEPREFIX=	p5-

MAINTAINER=	otaviof@gmail.com
COMMENT=	Provides an API for Git that uses Perl data structures

BUILD_DEPENDS=	\
	git:${PORTSDIR}/devel/git \
	${SITE_PERL}/ExtUtils/MakeMaker.pm:${PORTSDIR}/devel/p5-ExtUtils-MakeMaker \
	${SITE_PERL}/File/pushd.pm:${PORTSDIR}/devel/p5-File-pushd
RUN_DEPENDS=	${BUILD_DEPENDS}

USE_PERL=yes
PERL_CONFIGURE=	yes

MAN3=		Git::Wrapper.3

.include <bsd.port.mk>
