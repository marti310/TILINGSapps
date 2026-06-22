# Automatic Enumeration of Tilings by Polyominoes
* Based on [this paper](https://arxiv.org/abs/) by [Lucy Martinez](https://marti310.github.io/ "Lucy")

## Usage    
* Example using TILINGSapps.txt. Save this file as  TILINGSapps.txt to use it and stay in the same directory. Get into Mape and type:

``` read `TILINGSapps.txt:` ```

* The following will be prompted

```
                First Written: Jan. 2006: tested for Maple 10
                   Version of Jan. , 2006:

                This is TILINGS, A Maple package
accompanying Shalsoh B. Ekhad and Doron Zeilberger's  article: 
                    "Automatic CounTilings" 

                -------------------------------
        Version of Sept. 30, 2015, procedure Dimer added
                -------------------------------

        The most current version is available on WWW at:
    http://www.math.rutgers.edu/~zeilberg/tokhniot/TILINGS .
Please report all bugs to: zeilberg at math dot rutgers dot edu .

      For general help, and a list of the MAIN functions,
 type "ezra();". For specific help type "ezra(procedure_name);" 
     For a list of the supporting functions type: ezra1();
   ----------------------------------------------------------

NOTE: The above script is for a Maple package separate from the one below (see note below).

   ----------------------------------------------------------

  This is TILINGSapps.txt, a Maple package, accompanying the article:
        Automatic Enumeration of Tilings by Polyominoes
                       by Lucy Martinez.
        This Maple package, as well as the article, are 
                        available from:
            https://github.com/marti310/TILINGSapps

NOTE: This package and the accompanying paper are applications of the 2006 paper written by
    Shalosh B. Ekhad and Doron Zeilberger titled Automatic CounTilings.

      Please report bugs to lucyadrianamartinez@gmail.com 

                 -----------------------------

    For a list of the procedures type Help(), for help with
        a specific procedure, type Help(procedure_name)

                 -----------------------------
                 -----------------------------


For a list of the supporting procedures type Help1(), for help with
        a specific procedure, type Help(procedure_name)

                 -----------------------------


```

* Inputting `GFrot(4,{[0,0],[1,0],[0,1],[0,2]},t); `, outputs the generating function from the recent American Mathematical Monthly paper (found [here](https://doi.org/10.1080/00029890.2025.2600916)), which is the generating function for the number of tilings of a 2n by 4 rectangle using L-tetrominoes, where only rotations are allowed.

Input:

```
GFrot(4,{[0,0],[1,0],[0,1],[0,2]},t);
```

Output:

```
-(t^4 - 1)/(t^8 + t^6 - 3*t^4 - t^2 + 1)
```
