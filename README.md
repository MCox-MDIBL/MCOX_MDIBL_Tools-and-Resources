# Introduction
This is the repository in which Matthew Cox has stored various tools and resources available as scripts, worksheets, or R markdowns. 
These tools are useful for bioinformaticians and data analysts within molecular and biomediacal research. 
If you find any of these tools to be beneficial to your research, or if you find nuances which are undefined or broken, please let me know!

**My email: mcox@mdibl.org**

# Files of Note

qRT-PCR analysis automation worksheet: Excel workbook

- The qRT-PCR analysis automation worksheet takes input from the LightCycler480 spectrophotometer after a qRT-PCR run.
  - The input is specifically the table produced after analyzing the plate's Cq values via Analysis -> Abs Quant/2nd Dirivative Max for All Samples -> Calculate.
  - The order and arrangement of samples or target genes is unimportant in this original table, however, their order will be crucial within this automated worksheet.
    - For example: This sheet asks that the genes targetted in your qPCR experiment are arranged such that the Housekeeper gene will be in cell 'K2', at the top of the list of target genes.
  - Follow all directions on the first sheet of the workbook, and your final calculations will be formatted and output on the final sheet.



