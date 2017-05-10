# vim-listtrans

A plugin manager compatible version of [Damian Conway's listtrans
plugin](https://github.com/thoughtstream/Damian-Conway-s-Vim-Setup/blob/master/plugin/listtrans.vim)

## Usage

    nmap <SOMEKEY>  :call ListTrans_toggle_format()<CR>
    vmap <SOMEKEY>  :call ListTrans_toggle_format('visual')<CR>

For example:

    nmap  ;l   :call ListTrans_toggle_format()<CR>
    vmap  ;l   :call ListTrans_toggle_format('visual')<CR>
