# CBT491
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 491 is from Andy Robertson and contains a "lite" version  *   FILE 491
//*           of XMITIP which is written in COBOL.  Lionel Dyck's   *   FILE 491
//*           "original" version of XMITIP is on File 314 of this   *   FILE 491
//*           tape.  Lionel's (File 314) version is written in      *   FILE 491
//*           REXX.  These programs allow the sending of email      *   FILE 491
//*           messages from your MVS machine if you have an SMTP    *   FILE 491
//*           server running.                                       *   FILE 491
//*                                                                 *   FILE 491
//*           This file has been modified to include Andy's         *   FILE 491
//*           BATCHART package too.  See below for explanation.     *   FILE 491
//*                                                                 *   FILE 491
//*     Andy Robertson <andywrobertson@clara.co.uk>                 *   FILE 491
//*                                                                 *   FILE 491
//*     home site:                                                  *   FILE 491
//*         http://home.clara.net/andywrobertson/mvsindex.html      *   FILE 491
//*                                                                 *   FILE 491
//*   Note:  The following packages are in PDSLOAD format, which    *   FILE 491
//*          is a modified IEBUPDTE format that preserves ISPF      *   FILE 491
//*          statistics.  The PDSLOAD program load module is        *   FILE 491
//*          included in this pds, and a sample job to create the   *   FILE 491
//*          installation pds'es for the packages is in member      *   FILE 491
//*          $PDSLOAD.  Modify that member and run the job....      *   FILE 491
//*                                                                 *   FILE 491
//*     LECH     - A sample LE condition handler.  Code two COPY    *   FILE 491
//*                statements in your cobol mainline.  Interrupts   *   FILE 491
//*                will be intercepted with a dump and a message    *   FILE 491
//*                and your program will continue to run.           *   FILE 491
//*                                                                 *   FILE 491
//*     XMITMAIL - a "lite, fast" version of XMITIP, written in     *   FILE 491
//*                COBOL, callable from any HLL in batch or         *   FILE 491
//*                CICS.  Attachments only supported if you         *   FILE 491
//*                format them yourself.                            *   FILE 491
//*                                                                 *   FILE 491
//*     XMITCICS - an interface to run XMITMAIL from CICS.          *   FILE 491
//*                                                                 *   FILE 491
//*     BATCHART - a member in PDSLOAD format which contains COBOL  *   FILE 491
//*                source to produce 3270-displayable pictures.     *   FILE 491
//*                                                                 *   FILE 491
//*        BATCHART can be used to create GDFs in batch,            *   FILE 491
//*        using an input file of commands.                         *   FILE 491
//*                                                                 *   FILE 491
//*        The GDFs can be displayed on a 3720-type terminal,       *   FILE 491
//*        printed on an AFP printer, plotted, or saved as          *   FILE 491
//*        members of a PDS.  Saved PDS members can later be        *   FILE 491
//*        converted to .gif files by the IBM-provided              *   FILE 491
//*        ADMUGIF utility                                          *   FILE 491
//*                                                                 *   FILE 491
//*        BATCHART needs LE, GDDM and GDDM-PGF.                    *   FILE 491
//*                                                                 *   FILE 491
//*        To generate the BATCHART installation pds, just run the  *   FILE 491
//*        job $PDSLOAD.  This will generate the other pds'es also. *   FILE 491
//*                                                                 *   FILE 491
```
