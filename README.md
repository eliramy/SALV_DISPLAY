# SALV_DISPLAY Encapsulation - Simple SALV Display Version 1.0

Option1 file: YCL_SHOW_SALV.txt -> call static method show_salv -> Only for display ALV.

Option2 file: YCL_SHOW_SALV_INS -> Abstract Class Inherit this class and do Redefinition
1) Method on_link_click for HOTSPOT action.
2) Method on_user_command for salv new button event. 

Gernal Info. :
From SAP Netweaver 7.0 & above (Include S/4 HANA)

fill parameter - > IR_SALV type ref to DATA -> Example internal table convert -> ref #( gt_tab ) or old syntax GET REFERENCE OF gt_tab INTO IR_SALV.

Enjoy :)
