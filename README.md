# Proteomics

**Original Paper**: Bueno-Alvez et al. (2023). "Next generation pan-cancer 
blood proteome profiling using proximity extension assay."   
*Nature Communications*. https://doi.org/10.1038/s41467-023-39765-y

**Original Code**: https://github.com/buenoalvezm/Pan-cancer-profiling

Replace `themes$main()` to `theme_bw()` in cancer_volcano function to fix the error below:

> Error in `method(update_ggplot, list(ggplot2::theme, ggplot2::ggplot))`:  
> ! Can't merge the `plot.subtitle` theme element.  
> Caused by error:  
> ! `object` must be an <S7_object>, not a S3<element_text/element>  
> Run `rlang::last_trace()` to see where the error occurred.  
> Warning message:  
> themes$main is not a valid theme.  
> Please use `theme()` to construct themes.

