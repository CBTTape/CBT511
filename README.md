# CBT511
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 511 is from Geoffrey McIntyre, and contains an ISPF       *   FILE 511
//*           based VSAM Space Manager application, written in      *   FILE 511
//*           COBOL.                                                *   FILE 511
//*                                                                 *   FILE 511
//*           email:  geoffrey.mcintyre@firstunion.com              *   FILE 511
//*                                                                 *   FILE 511
//*      Function/Features of VSAMPGM                               *   FILE 511
//*                                                                 *   FILE 511
//*      1) VSAMPGM can be used in foreground for individual        *   FILE 511
//*         files to:                                               *   FILE 511
//*                                                                 *   FILE 511
//*         a)  examine how efficiently the file is allocated,      *   FILE 511
//*             and how much each component costs (used space       *   FILE 511
//*             cost, free space cost, unused space cost, etc.)     *   FILE 511
//*         b)  Run an index analysis to see if the index CI is     *   FILE 511
//*             adequate to store all of the keys of a data CI.     *   FILE 511
//*         c)  Run a job to calculate a file's true average        *   FILE 511
//*             LRECL                                               *   FILE 511
//*         d)  Run a job to reorganize the file with 18K data      *   FILE 511
//*             cisize and 2K index cisize                          *   FILE 511
//*                                                                 *   FILE 511
//*      2) VSAMPGM can be used in a production batch step to:      *   FILE 511
//*                                                                 *   FILE 511
//*         a)  monitor a list of given VSAM datasets and print     *   FILE 511
//*             out exception reports                               *   FILE 511
//*         b)  automatically generate fresh delete/define cards,   *   FILE 511
//*             based on the exception report, as well as reorg     *   FILE 511
//*             JCL.                                                *   FILE 511
//*         c)  save the delete/define cards in a PDS (specified    *   FILE 511
//*             in the control cards; the PDS and member name is    *   FILE 511
//*             specified on each control card)                     *   FILE 511
//*         d)  step can run in simulation mode (produces the       *   FILE 511
//*             exception change reports, but not the reorg JCL)    *   FILE 511
//*         e)  supports comment cards in the control card deck     *   FILE 511
//*         f)  automatically submits (internal reader) the         *   FILE 511
//*             reorg JCL if not in simulation mode                 *   FILE 511
//*         g)  Simulation mode can be turned on or off at the      *   FILE 511
//*             file level                                          *   FILE 511
//*                                                                 *   FILE 511
//*      3) Datapacker (Data Accelerator) Support                   *   FILE 511
//*                                                                 *   FILE 511
```
