
Makefiles for  libpng version 1.6.34 - September 29, 2017

pnglibconf.h.prebuilt       =>  Stores configuration settings
makefile.linux    =>  Linux / ELF makefile
(gcc, creates libpng16.so.16.1.6.34)
	makefile.linux - opt =>  Linux / ELF makefile with hardware optimizations on
	(gcc, creates libpng16.so.16.1.6.34)
	makefile.gcc      =>  Generic makefile(gcc, creates static libpng.a)
	makefile.knr      =>  Archaic UNIX Makefile that converts files with
	ansi2knr(Requires ansi2knr.c from
			 ftp : //ftp.cs.wisc.edu/ghost)
			 makefile.acorn    =>  Acorn makefile
			 makefile.aix      =>  AIX / gcc makefile
			 makefile.amiga    =>  Amiga makefile
			 makefile.atari    =>  Atari makefile
			 makefile.bc32     =>  32 - bit Borland C++ (all modules compiled in C mode)
			 makefile.beos     =>  beos makefile
			 makefile.bor      =>  Borland makefile(uses bcc)
			 makefile.cegcc    =>  minge32ce for Windows CE makefile
			 makefile.darwin   =>  Darwin makefile, can use on MacosX
			 makefile.dec      =>  DEC Alpha UNIX makefile
			 makefile.dj2      =>  DJGPP 2 makefile
			 makefile.freebsd  =>  FreeBSD makefile
			 makefile.gcc      =>  Generic gcc makefile
			 makefile.hpgcc    =>  HPUX makefile using gcc
			 makefile.hpux     =>  HPUX(10.20 and 11.00) makefile
			 makefile.hp64     =>  HPUX(10.20 and 11.00) makefile, 64 - bit
			 makefile.ibmc     =>  IBM C / C++ version 3.x for Win32 and OS / 2(static)
				 makefile.intel    =>  Intel C / C++ version 4.0 and later
				 makefile.mips     =>  MIPS makefile
				 makefile.msc      =>  Microsoft C makefile
				 makefile.netbsd   =>  NetBSD / cc makefile, makes libpng.so.
				 makefile.openbsd  =>  OpenBSD makefile
				 makefile.os2      =>  OS / 2 Makefile(gcc and emx, requires libpng.def)
				 makefile.sco      =>  For SCO OSr5  ELF and Unixware 7 with Native cc
				 makefile.sggcc    =>  Silicon Graphics(gcc,
						 creates libpng16.so.16.1.6.34)
				 makefile.sgi      =>  Silicon Graphics IRIX makefile(cc, creates static lib)
				 makefile.solaris  =>  Solaris 2.X makefile(gcc,
						 creates libpng16.so.16.1.6.34)
				 makefile.so9      =>  Solaris 9 makefile(gcc,
						 creates libpng16.so.16.1.6.34)
				 makefile.std      =>  Generic UNIX makefile(cc, creates static libpng.a)
				 makefile.sunos    =>  Sun makefile
				 makefile.32sunu   =>  Sun Ultra 32 - bit makefile
				 makefile.64sunu   =>  Sun Ultra 64 - bit makefile
				 makefile.tc3      =>  Turbo C 3.0 makefile
				 makefile.vcwin32  =>  makefile for Microsoft Visual C++ 4.0 and later
					 makevms.com       =>  VMS build script
					 smakefile.ppc     =>  AMIGA smakefile for SAS C V6.58 / 7.00 PPC compiler
						 (Requires SCOPTIONS, copied from scripts / SCOPTIONS.ppc)

						 Other supporting scripts :
						 README.txt        =>  This file
						 descrip.mms       =>  VMS makefile for MMS or MMK
							 libpng - config - body.in => used by several makefiles to create libpng - config
							 libpng - config - head.in => used by several makefiles to create libpng - config
							 libpng.pc.in      =>  Used by several makefiles to create libpng.pc
							 pngwin.rc         =>  Used by the visualc71 project.
							 pngwin.def        =>  Used by makefile.os2
							 pngwin.dfn        =>  Used to maintain pngwin.def
							 SCOPTIONS.ppc     =>  Used with smakefile.ppc

							 checksym.awk       =>  Used for maintaining pnglibconf.h
								 def.dfn            =>  Used for maintaining pnglibconf.h
									 options.awk        =>  Used for maintaining pnglibconf.h
										 pnglibconf.dfa     =>  Used for maintaining pnglibconf.h
											 pnglibconf.mak     =>  Used for maintaining pnglibconf.h
												 sym.dfn            =>  Used for symbol versioning
													 symbols.def        =>  Used for symbol versioning
														 symbols.dfn        =>  Used for symbol versioning
															 vers.dfn           =>  Used for symbol versioning

																 libtool.m4        =>  Used by autoconf tools
																 ltoptions.m4      =>  Used by autoconf tools
																 ltsugar.m4        =>  Used by autoconf tools
																 ltversion.m4      =>  Used by autoconf tools
																 lt~obsolete.m4    =>  Used by autoconf tools

																 intprefix.dfn     =>  Used by autoconf tools
																 macro.lst         =>  Used by autoconf tools
																 prefix.dfn        =>  Used by autoconf tools


																 Further information can be found in comments in the individual makefiles.
