goal: have a widget that shows "how" I'm typing
	- answers questions like "what movement command was that in vim?"
	- persists long enough for seqs to be grokked

todo:
- bouncing 'j/k' should just flash the existing 'j' and 'k' elements
- 'shift+5' should be '%'
- bug: spam >> wait for clear >> input-is-ignored >> spam >> input-is-recognized
- since combo strokes are wider than singles, a seq of many combos followed by
  singles shifts the 'cursor' left as typing happens ;;; jarring
		- fix: make everything fixedwidth
		- fix: align list items to the right
- 'j + space' ==> ' + space' ... O_o
