Two files could be found everywhere:  
`*.old` - the old (original) file  
`*.new` - the new (modified) file  
  
Use any of the software to find the differences between `.new` and `.old` files. 
Differences are easy to find with:  
- KDiff3 ( http://kdiff3.sourceforge.net/ )  
- WinMerge ( http://winmerge.org/ )  
- ExamDiff ( http://www.prestosoft.com/edp_examdiff.asp )  
- Any other tool  

Differences of every `.old` and `.new` pair needs to be appended into:  
`inc\structure\header-extensions.php.*` -> `wp-content\themes\wp-portfolio\inc\structure\header-extensions.php`  
`root--wp-includes\category-template.php.*` -> `wp-includes\category-template.php`  
`style.css.*` -> `wp-content\themes\wp-portfolio\style.css`  
  
Sure, there may be some other ways to make this type of change more user-friendly. Maybe something useful could be found in here: https://codex.wordpress.org/Child_Themes  
However, the other update on this template may not be needed at all. So let it be like that for a while.
