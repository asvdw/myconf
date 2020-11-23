#toggle fold:za
# Tmux {{{

default prefix: <C>-b

###  session
tmux new -s session_name
tmux a -s session_name
:choose-session / <p>( <p>)
:rename-session <p>$

### windows
c create
, rename
& close
p n <number> switch

### panes
split: %" (default) - vh (custom)
reload conf: r (custom)
resize: +-<>=| (custom)
select: hjkl arrows (custom)
<p>q selection numerique
; toggle
z zoom
! convert to window
### copy mode
<p>[ (default) <p><Esc> (custom)
#}}}
