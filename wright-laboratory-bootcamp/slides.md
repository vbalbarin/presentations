<!DOCTYPE html><html lang="en-US"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,height=device-height,initial-scale=1.0"><meta name="apple-mobile-web-app-capable" content="yes"><meta http-equiv="X-UA-Compatible" content="ie=edge"><meta property="og:type" content="website"><meta name="twitter:card" content="summary"><style>@media screen{body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button{-webkit-tap-highlight-color:transparent;-webkit-appearance:none;appearance:none;background-color:transparent;border:0;color:inherit;cursor:pointer;font-size:inherit;opacity:.8;outline:none;padding:0;transition:opacity .2s linear}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button:disabled,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button:disabled,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button:disabled,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button:disabled{cursor:not-allowed;opacity:.15!important}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button:hover,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button:hover,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button:hover,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button:hover{opacity:1}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button:hover:active,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button:hover:active,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button:hover:active,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button:hover:active{opacity:.6}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button:hover:not(:disabled),body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button:hover:not(:disabled),body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button:hover:not(:disabled),body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button:hover:not(:disabled){transition:none}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=prev],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=prev],body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button.bespoke-marp-presenter-info-page-prev{background:transparent url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48cGF0aCBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSI1IiBkPSJNNjggOTAgMjggNTBsNDAtNDAiLz48L3N2Zz4=") no-repeat 50%;background-size:contain;overflow:hidden;text-indent:100%;white-space:nowrap}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=next],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=next],body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button.bespoke-marp-presenter-info-page-next{background:transparent url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48cGF0aCBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSI1IiBkPSJtMzIgOTAgNDAtNDAtNDAtNDAiLz48L3N2Zz4=") no-repeat 50%;background-size:contain;overflow:hidden;text-indent:100%;white-space:nowrap}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=fullscreen],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=fullscreen]{background:transparent url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48ZGVmcz48c3R5bGU+LmF7ZmlsbDpub25lO3N0cm9rZTojZmZmO3N0cm9rZS1saW5lY2FwOnJvdW5kO3N0cm9rZS1saW5lam9pbjpyb3VuZDtzdHJva2Utd2lkdGg6NXB4fTwvc3R5bGU+PC9kZWZzPjxyZWN0IHdpZHRoPSI4MCIgaGVpZ2h0PSI2MCIgeD0iMTAiIHk9IjIwIiBjbGFzcz0iYSIgcng9IjUuNjciLz48cGF0aCBkPSJNNDAgNzBIMjBWNTBtMjAgMEwyMCA3MG00MC00MGgyMHYyMG0tMjAgMCAyMC0yMCIgY2xhc3M9ImEiLz48L3N2Zz4=") no-repeat 50%;background-size:contain;overflow:hidden;text-indent:100%;white-space:nowrap}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button.exit[data-bespoke-marp-osc=fullscreen],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button.exit[data-bespoke-marp-osc=fullscreen]{background-image:url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48ZGVmcz48c3R5bGU+LmF7ZmlsbDpub25lO3N0cm9rZTojZmZmO3N0cm9rZS1saW5lY2FwOnJvdW5kO3N0cm9rZS1saW5lam9pbjpyb3VuZDtzdHJva2Utd2lkdGg6NXB4fTwvc3R5bGU+PC9kZWZzPjxyZWN0IHdpZHRoPSI4MCIgaGVpZ2h0PSI2MCIgeD0iMTAiIHk9IjIwIiBjbGFzcz0iYSIgcng9IjUuNjciLz48cGF0aCBkPSJNMjAgNTBoMjB2MjBtLTIwIDAgMjAtMjBtNDAgMEg2MFYzMG0yMCAwTDYwIDUwIiBjbGFzcz0iYSIvPjwvc3ZnPg==")}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=presenter],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=presenter]{background:transparent url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48cGF0aCBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSI1IiBkPSJNODcuOCA0Ny41Qzg5IDUwIDg3LjcgNTIgODUgNTJIMzVhOC43IDguNyAwIDAgMS03LjItNC41bC0xNS42LTMxQzExIDE0IDEyLjIgMTIgMTUgMTJoNTBhOC44IDguOCAwIDAgMSA3LjIgNC41ek02MCA1MnYzNm0tMTAgMGgyME00NSA0MmgyMCIvPjwvc3ZnPg==") no-repeat 50%;background-size:contain;overflow:hidden;text-indent:100%;white-space:nowrap}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button.bespoke-marp-presenter-note-bigger{background:transparent url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48cGF0aCBzdHJva2U9IiNmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSI1IiBkPSJNMTIgNTBoODBNNTIgOTBWMTAiLz48L3N2Zz4=") no-repeat 50%;background-size:contain;overflow:hidden;text-indent:100%;white-space:nowrap}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button.bespoke-marp-presenter-note-smaller{background:transparent url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48cGF0aCBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSI1IiBkPSJNMTIgNTBoODAiLz48L3N2Zz4=") no-repeat 50%;background-size:contain;overflow:hidden;text-indent:100%;white-space:nowrap}}@keyframes __bespoke_marp_transition_reduced_outgoing__{0%{opacity:1}to{opacity:0}}@keyframes __bespoke_marp_transition_reduced_incoming__{0%{mix-blend-mode:plus-lighter;opacity:0}to{mix-blend-mode:plus-lighter;opacity:1}}.bespoke-marp-note,.bespoke-marp-osc,.bespoke-progress-parent{display:none;transition:none}@media screen{::view-transition-group(*){animation-duration:var(--marp-bespoke-transition-animation-duration,.5s);animation-timing-function:ease}::view-transition-new(*),::view-transition-old(*){animation-delay:0s;animation-direction:var(--marp-bespoke-transition-animation-direction,normal);animation-duration:var(--marp-bespoke-transition-animation-duration,.5s);animation-fill-mode:both;animation-name:var(--marp-bespoke-transition-animation-name,var(--marp-bespoke-transition-animation-name-fallback,__bespoke_marp_transition_no_animation__));mix-blend-mode:normal}::view-transition-old(*){--marp-bespoke-transition-animation-name-fallback:__bespoke_marp_transition_reduced_outgoing__;animation-timing-function:ease}::view-transition-new(*){--marp-bespoke-transition-animation-name-fallback:__bespoke_marp_transition_reduced_incoming__;animation-timing-function:ease}::view-transition-new(root),::view-transition-old(root){animation-timing-function:linear}::view-transition-new(__bespoke_marp_transition_osc__),::view-transition-old(__bespoke_marp_transition_osc__){animation-duration:0s!important;animation-name:__bespoke_marp_transition_osc__!important}::view-transition-new(__bespoke_marp_transition_osc__){opacity:0!important}.bespoke-marp-transition-warming-up::view-transition-group(*),.bespoke-marp-transition-warming-up::view-transition-new(*),.bespoke-marp-transition-warming-up::view-transition-old(*){animation-play-state:paused!important}body,html{height:100%;margin:0}body{background:#000;overflow:hidden}svg.bespoke-marp-slide{content-visibility:hidden;opacity:0;pointer-events:none;z-index:-1}svg.bespoke-marp-slide:not(.bespoke-marp-active) *{view-transition-name:none!important}svg.bespoke-marp-slide.bespoke-marp-active{content-visibility:visible;opacity:1;pointer-events:auto;z-index:0}svg.bespoke-marp-slide.bespoke-marp-active.bespoke-marp-active-ready *{animation-name:__bespoke_marp__!important}@supports not (content-visibility:hidden){svg.bespoke-marp-slide[data-bespoke-marp-load=hideable]{display:none}svg.bespoke-marp-slide[data-bespoke-marp-load=hideable].bespoke-marp-active{display:block}}}@media screen and (prefers-reduced-motion:reduce){svg.bespoke-marp-slide *{view-transition-name:none!important}}@media screen{[data-bespoke-marp-fragment=inactive]{visibility:hidden}body[data-bespoke-view=""] .bespoke-marp-parent,body[data-bespoke-view=next] .bespoke-marp-parent{inset:0;position:absolute}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc{view-transition-name:__bespoke_marp_transition_osc__;background:rgba(0,0,0,.65);border-radius:7px;bottom:50px;color:#fff;contain:paint;display:block;font-family:Helvetica,Arial,sans-serif;font-size:16px;left:50%;line-height:0;opacity:1;padding:12px;position:absolute;touch-action:manipulation;transform:translateX(-50%);transition:opacity .2s linear;-webkit-user-select:none;user-select:none;white-space:nowrap;will-change:transform;z-index:1}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>*,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>*{margin-left:6px}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>:first-child,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>:first-child{margin-left:0}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>span,body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>span{opacity:.8}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>span[data-bespoke-marp-osc=page],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>span[data-bespoke-marp-osc=page]{display:inline-block;min-width:140px;text-align:center}body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=fullscreen],body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=next],body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=presenter],body[data-bespoke-view=""] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=prev],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=fullscreen],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=next],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=presenter],body[data-bespoke-view=next] .bespoke-marp-parent>.bespoke-marp-osc>button[data-bespoke-marp-osc=prev]{height:32px;line-height:32px;width:32px}body[data-bespoke-view=""] .bespoke-marp-parent.bespoke-marp-inactive,body[data-bespoke-view=next] .bespoke-marp-parent.bespoke-marp-inactive{cursor:none}body[data-bespoke-view=""] .bespoke-marp-parent.bespoke-marp-inactive>.bespoke-marp-osc,body[data-bespoke-view=next] .bespoke-marp-parent.bespoke-marp-inactive>.bespoke-marp-osc{opacity:0;pointer-events:none}body[data-bespoke-view=""] svg.bespoke-marp-slide,body[data-bespoke-view=next] svg.bespoke-marp-slide{height:100%;left:0;position:absolute;top:0;width:100%}body[data-bespoke-view=""] .bespoke-progress-parent{background:#222;display:flex;height:5px;width:100%}body[data-bespoke-view=""] .bespoke-progress-parent+.bespoke-marp-parent{top:5px}body[data-bespoke-view=""] .bespoke-progress-parent .bespoke-progress-bar{background:#0288d1;flex:0 0 0;transition:flex-basis .2s cubic-bezier(0,1,1,1)}body[data-bespoke-view=next]{background:transparent}body[data-bespoke-view=presenter]{background:#161616}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container{display:grid;font-family:Helvetica,Arial,sans-serif;grid-template:"current dragbar next" minmax(140px,1fr) "current dragbar note" 2fr "info    dragbar note" 3em;grid-template-columns:minmax(3px,var(--bespoke-marp-presenter-split-ratio,66%)) 0 minmax(3px,1fr);height:100%;left:0;position:absolute;top:0;width:100%}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-parent{grid-area:current;overflow:hidden;position:relative}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-parent svg.bespoke-marp-slide{height:calc(100% - 40px);left:20px;pointer-events:none;position:absolute;top:20px;-webkit-user-select:none;user-select:none;width:calc(100% - 40px)}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-parent svg.bespoke-marp-slide.bespoke-marp-active{filter:drop-shadow(0 3px 10px rgba(0,0,0,.5))}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-dragbar-container{background:#0288d1;cursor:col-resize;grid-area:dragbar;margin-left:-3px;opacity:0;position:relative;transition:opacity .4s linear .1s;width:6px;z-index:10}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-dragbar-container:hover{opacity:1}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-dragbar-container.active{opacity:1;transition-delay:0s}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-next-container{background:#222;cursor:pointer;display:none;grid-area:next;overflow:hidden;position:relative}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-next-container.active{display:block}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-next-container iframe.bespoke-marp-presenter-next{background:transparent;border:0;display:block;filter:drop-shadow(0 3px 10px rgba(0,0,0,.5));height:calc(100% - 40px);left:20px;pointer-events:none;position:absolute;top:20px;-webkit-user-select:none;user-select:none;width:calc(100% - 40px)}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container{background:#222;color:#eee;grid-area:note;position:relative;z-index:1}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container button{height:1.5em;line-height:1.5em;width:1.5em}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-presenter-note-wrapper{display:block;inset:0;position:absolute}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-presenter-note-buttons{background:rgba(0,0,0,.65);border-radius:4px;bottom:0;display:flex;gap:4px;margin:12px;opacity:0;padding:6px;pointer-events:none;position:absolute;right:0;transition:opacity .2s linear}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-presenter-note-buttons:focus-within,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-presenter-note-wrapper:focus-within+.bespoke-marp-presenter-note-buttons,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container:hover .bespoke-marp-presenter-note-buttons{opacity:1;pointer-events:auto}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note{word-wrap:break-word;box-sizing:border-box;font-size:calc(1.1em*var(--bespoke-marp-note-font-scale, 1));height:calc(100% - 40px);margin:20px;overflow:auto;padding-right:3px;scrollbar-color:hsla(0,0%,93%,.5) transparent;scrollbar-width:thin;white-space:pre-wrap;width:calc(100% - 40px)}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note::-webkit-scrollbar{width:6px}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note::-webkit-scrollbar-track{background:transparent}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note::-webkit-scrollbar-thumb{background:hsla(0,0%,93%,.5);border-radius:6px}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note:empty{pointer-events:none}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note.active{display:block}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note p:first-child{margin-top:0}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-note-container .bespoke-marp-note p:last-child{margin-bottom:0}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container{align-items:center;box-sizing:border-box;color:#eee;display:flex;flex-wrap:nowrap;grid-area:info;justify-content:center;overflow:hidden;padding:0 10px}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-page,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-time,body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-timer{box-sizing:border-box;display:block;padding:0 10px;white-space:nowrap;width:100%}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container button{height:1.5em;line-height:1.5em;width:1.5em}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-page{order:2;text-align:center}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-page .bespoke-marp-presenter-info-page-text{display:inline-block;min-width:120px;text-align:center}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-time{color:#999;order:1;text-align:left}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-timer{color:#999;order:3;text-align:right}body[data-bespoke-view=presenter] .bespoke-marp-presenter-container .bespoke-marp-presenter-info-container .bespoke-marp-presenter-info-timer:hover{cursor:pointer}}@media print{.bespoke-marp-presenter-info-container,.bespoke-marp-presenter-next-container,.bespoke-marp-presenter-note-container{display:none}}</style><style>div#\:\$p>svg>foreignObject>section{width:1280px;height:720px;box-sizing:border-box;overflow:hidden;position:relative;scroll-snap-align:center center}div#\:\$p>svg>foreignObject>section:after{bottom:0;content:attr(data-marpit-pagination);padding:inherit;pointer-events:none;position:absolute;right:0}div#\:\$p>svg>foreignObject>section:not([data-marpit-pagination]):after{display:none}/* Normalization */div#\:\$p>svg>foreignObject>section :is(h1,marp-h1){font-size:2em;margin:0.67em 0}div#\:\$p>svg>foreignObject>section video::-webkit-media-controls{will-change:transform}@page{size:1280px 720px;margin:0}@media print{body,html{background-color:#fff;margin:0;page-break-inside:avoid;break-inside:avoid-page}div#\:\$p>svg>foreignObject>section{page-break-before:always;break-before:page}div#\:\$p>svg>foreignObject>section,div#\:\$p>svg>foreignObject>section *{-webkit-print-color-adjust:exact!important;animation-delay:0s!important;animation-duration:0s!important;color-adjust:exact!important;transition:none!important}div#\:\$p>svg[data-marpit-svg]{display:block;height:100vh;width:100vw}}div#\:\$p>svg>foreignObject>section img[data-marp-twemoji]{background:transparent;height:1em;margin:0 .05em 0 .1em;vertical-align:-.1em;width:1em}
/*!
 * Marp default theme.
 *
 * @theme default
 * @author Yuki Hattori
 *
 * @auto-scaling true
 * @size 16:9 1280px 720px
 * @size 4:3 960px 720px
 */div#\:\$p>svg>foreignObject>section{--color-prettylights-syntax-comment:#6e7781;--color-prettylights-syntax-constant:#0550ae;--color-prettylights-syntax-entity:#8250df;--color-prettylights-syntax-storage-modifier-import:#24292f;--color-prettylights-syntax-entity-tag:#116329;--color-prettylights-syntax-keyword:#cf222e;--color-prettylights-syntax-string:#0a3069;--color-prettylights-syntax-variable:#953800;--color-prettylights-syntax-brackethighlighter-unmatched:#82071e;--color-prettylights-syntax-invalid-illegal-text:#f6f8fa;--color-prettylights-syntax-invalid-illegal-bg:#82071e;--color-prettylights-syntax-carriage-return-text:#f6f8fa;--color-prettylights-syntax-carriage-return-bg:#cf222e;--color-prettylights-syntax-string-regexp:#116329;--color-prettylights-syntax-markup-list:#3b2300;--color-prettylights-syntax-markup-heading:#0550ae;--color-prettylights-syntax-markup-italic:#24292f;--color-prettylights-syntax-markup-bold:#24292f;--color-prettylights-syntax-markup-deleted-text:#82071e;--color-prettylights-syntax-markup-deleted-bg:#ffebe9;--color-prettylights-syntax-markup-inserted-text:#116329;--color-prettylights-syntax-markup-inserted-bg:#dafbe1;--color-prettylights-syntax-markup-changed-text:#953800;--color-prettylights-syntax-markup-changed-bg:#ffd8b5;--color-prettylights-syntax-markup-ignored-text:#eaeef2;--color-prettylights-syntax-markup-ignored-bg:#0550ae;--color-prettylights-syntax-meta-diff-range:#8250df;--color-prettylights-syntax-brackethighlighter-angle:#57606a;--color-prettylights-syntax-sublimelinter-gutter-mark:#8c959f;--color-prettylights-syntax-constant-other-reference-link:#0a3069;--color-fg-default:#24292f;--color-fg-muted:#57606a;--color-fg-subtle:#6e7781;--color-canvas-default:#fff;--color-canvas-subtle:#f6f8fa;--color-border-default:#d0d7de;--color-border-muted:#d8dee4;--color-neutral-muted:rgba(175,184,193,.2);--color-accent-fg:#0969da;--color-accent-emphasis:#0969da;--color-attention-subtle:#fff8c5;--color-danger-fg:#cf222e;color-scheme:light}div#\:\$p>svg>foreignObject>section:where(.invert){--color-prettylights-syntax-comment:#8b949e;--color-prettylights-syntax-constant:#79c0ff;--color-prettylights-syntax-entity:#d2a8ff;--color-prettylights-syntax-storage-modifier-import:#c9d1d9;--color-prettylights-syntax-entity-tag:#7ee787;--color-prettylights-syntax-keyword:#ff7b72;--color-prettylights-syntax-string:#a5d6ff;--color-prettylights-syntax-variable:#ffa657;--color-prettylights-syntax-brackethighlighter-unmatched:#f85149;--color-prettylights-syntax-invalid-illegal-text:#f0f6fc;--color-prettylights-syntax-invalid-illegal-bg:#8e1519;--color-prettylights-syntax-carriage-return-text:#f0f6fc;--color-prettylights-syntax-carriage-return-bg:#b62324;--color-prettylights-syntax-string-regexp:#7ee787;--color-prettylights-syntax-markup-list:#f2cc60;--color-prettylights-syntax-markup-heading:#1f6feb;--color-prettylights-syntax-markup-italic:#c9d1d9;--color-prettylights-syntax-markup-bold:#c9d1d9;--color-prettylights-syntax-markup-deleted-text:#ffdcd7;--color-prettylights-syntax-markup-deleted-bg:#67060c;--color-prettylights-syntax-markup-inserted-text:#aff5b4;--color-prettylights-syntax-markup-inserted-bg:#033a16;--color-prettylights-syntax-markup-changed-text:#ffdfb6;--color-prettylights-syntax-markup-changed-bg:#5a1e02;--color-prettylights-syntax-markup-ignored-text:#c9d1d9;--color-prettylights-syntax-markup-ignored-bg:#1158c7;--color-prettylights-syntax-meta-diff-range:#d2a8ff;--color-prettylights-syntax-brackethighlighter-angle:#8b949e;--color-prettylights-syntax-sublimelinter-gutter-mark:#484f58;--color-prettylights-syntax-constant-other-reference-link:#a5d6ff;--color-fg-default:#c9d1d9;--color-fg-muted:#8b949e;--color-fg-subtle:#6e7681;--color-canvas-default:#0d1117;--color-canvas-subtle:#161b22;--color-border-default:#30363d;--color-border-muted:#21262d;--color-neutral-muted:hsla(215,8%,47%,.4);--color-accent-fg:#58a6ff;--color-accent-emphasis:#1f6feb;--color-attention-subtle:rgba(187,128,9,.15);--color-danger-fg:#f85149;color-scheme:dark}div#\:\$p>svg>foreignObject>section{-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%;word-wrap:break-word;background-color:var(--color-canvas-default);color:var(--color-fg-default);font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Noto Sans,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji;font-size:16px;line-height:1.5;margin:0}div#\:\$p>svg>foreignObject>section{--marpit-root-font-size:16px}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1):hover .anchor .octicon-link:before,div#\:\$p>svg>foreignObject>section :is(h2,marp-h2):hover .anchor .octicon-link:before,div#\:\$p>svg>foreignObject>section :is(h3,marp-h3):hover .anchor .octicon-link:before,div#\:\$p>svg>foreignObject>section :is(h4,marp-h4):hover .anchor .octicon-link:before,div#\:\$p>svg>foreignObject>section :is(h5,marp-h5):hover .anchor .octicon-link:before,div#\:\$p>svg>foreignObject>section :is(h6,marp-h6):hover .anchor .octicon-link:before{background-color:currentColor;content:" ";display:inline-block;height:16px;-webkit-mask-image:url('data:image/svg+xml;charset=utf-8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 0 0 1.06 1.06l1.25-1.25a2 2 0 1 1 2.83 2.83l-2.5 2.5a2 2 0 0 1-2.83 0 .75.75 0 0 0-1.06 1.06 3.5 3.5 0 0 0 4.95 0l2.5-2.5a3.5 3.5 0 0 0-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 0 1 0-2.83l2.5-2.5a2 2 0 0 1 2.83 0 .75.75 0 0 0 1.06-1.06 3.5 3.5 0 0 0-4.95 0l-2.5 2.5a3.5 3.5 0 0 0 4.95 4.95l1.25-1.25a.75.75 0 0 0-1.06-1.06l-1.25 1.25a2 2 0 0 1-2.83 0z"/></svg>');mask-image:url('data:image/svg+xml;charset=utf-8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 0 0 1.06 1.06l1.25-1.25a2 2 0 1 1 2.83 2.83l-2.5 2.5a2 2 0 0 1-2.83 0 .75.75 0 0 0-1.06 1.06 3.5 3.5 0 0 0 4.95 0l2.5-2.5a3.5 3.5 0 0 0-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 0 1 0-2.83l2.5-2.5a2 2 0 0 1 2.83 0 .75.75 0 0 0 1.06-1.06 3.5 3.5 0 0 0-4.95 0l-2.5 2.5a3.5 3.5 0 0 0 4.95 4.95l1.25-1.25a.75.75 0 0 0-1.06-1.06l-1.25 1.25a2 2 0 0 1-2.83 0z"/></svg>');width:16px}div#\:\$p>svg>foreignObject>section details,div#\:\$p>svg>foreignObject>section figcaption,div#\:\$p>svg>foreignObject>section figure{display:block}div#\:\$p>svg>foreignObject>section summary{display:list-item}div#\:\$p>svg>foreignObject>section [hidden]{display:none!important}div#\:\$p>svg>foreignObject>section a{background-color:transparent;color:var(--color-accent-fg);text-decoration:none}div#\:\$p>svg>foreignObject>section abbr[title]{border-bottom:none;-webkit-text-decoration:underline dotted;text-decoration:underline dotted}div#\:\$p>svg>foreignObject>section b,div#\:\$p>svg>foreignObject>section strong{font-weight:var(--base-text-weight-semibold,600)}div#\:\$p>svg>foreignObject>section dfn{font-style:italic}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1){border-bottom:1px solid var(--color-border-muted);font-size:2em;font-weight:var(--base-text-weight-semibold,600);margin:.67em 0;padding-bottom:.3em}div#\:\$p>svg>foreignObject>section mark{background-color:var(--color-attention-subtle);color:var(--color-fg-default)}div#\:\$p>svg>foreignObject>section small{font-size:90%}div#\:\$p>svg>foreignObject>section sub,div#\:\$p>svg>foreignObject>section sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}div#\:\$p>svg>foreignObject>section sub{bottom:-.25em}div#\:\$p>svg>foreignObject>section sup{top:-.5em}div#\:\$p>svg>foreignObject>section img{background-color:var(--color-canvas-default);border-style:none;box-sizing:content-box;max-width:100%}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre),div#\:\$p>svg>foreignObject>section code,div#\:\$p>svg>foreignObject>section kbd,div#\:\$p>svg>foreignObject>section samp{font-family:monospace;font-size:1em}div#\:\$p>svg>foreignObject>section figure{margin:1em 40px}div#\:\$p>svg>foreignObject>section hr{background:transparent;background-color:var(--color-border-default);border:0;box-sizing:content-box;height:.25em;margin:24px 0;overflow:hidden;padding:0}div#\:\$p>svg>foreignObject>section input{font:inherit;font-family:inherit;font-size:inherit;line-height:inherit;margin:0;overflow:visible}div#\:\$p>svg>foreignObject>section [type=button],div#\:\$p>svg>foreignObject>section [type=reset],div#\:\$p>svg>foreignObject>section [type=submit]{-webkit-appearance:button}div#\:\$p>svg>foreignObject>section [type=checkbox],div#\:\$p>svg>foreignObject>section [type=radio]{box-sizing:border-box;padding:0}div#\:\$p>svg>foreignObject>section [type=number]::-webkit-inner-spin-button,div#\:\$p>svg>foreignObject>section [type=number]::-webkit-outer-spin-button{height:auto}div#\:\$p>svg>foreignObject>section [type=search]::-webkit-search-cancel-button,div#\:\$p>svg>foreignObject>section [type=search]::-webkit-search-decoration{-webkit-appearance:none}div#\:\$p>svg>foreignObject>section ::-webkit-input-placeholder{color:inherit;opacity:.54}div#\:\$p>svg>foreignObject>section ::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}div#\:\$p>svg>foreignObject>section a:hover{text-decoration:underline}div#\:\$p>svg>foreignObject>section ::-moz-placeholder{color:var(--color-fg-subtle);opacity:1}div#\:\$p>svg>foreignObject>section ::placeholder{color:var(--color-fg-subtle);opacity:1}div#\:\$p>svg>foreignObject>section hr:after,div#\:\$p>svg>foreignObject>section hr:before{content:"";display:table}div#\:\$p>svg>foreignObject>section hr:after{clear:both}div#\:\$p>svg>foreignObject>section table{border-collapse:collapse;border-spacing:0;display:block;max-width:100%;overflow:auto;width:-moz-max-content;width:max-content}div#\:\$p>svg>foreignObject>section td,div#\:\$p>svg>foreignObject>section th{padding:0}div#\:\$p>svg>foreignObject>section details summary{cursor:pointer}div#\:\$p>svg>foreignObject>section details:not([open])>:not(summary){display:none!important}div#\:\$p>svg>foreignObject>section [role=button]:focus,div#\:\$p>svg>foreignObject>section a:focus,div#\:\$p>svg>foreignObject>section input[type=checkbox]:focus,div#\:\$p>svg>foreignObject>section input[type=radio]:focus{box-shadow:none;outline:2px solid var(--color-accent-fg);outline-offset:-2px}div#\:\$p>svg>foreignObject>section [role=button]:focus:not(:focus-visible),div#\:\$p>svg>foreignObject>section a:focus:not(:focus-visible),div#\:\$p>svg>foreignObject>section input[type=checkbox]:focus:not(:focus-visible),div#\:\$p>svg>foreignObject>section input[type=radio]:focus:not(:focus-visible){outline:1px solid transparent}div#\:\$p>svg>foreignObject>section [role=button]:focus-visible,div#\:\$p>svg>foreignObject>section a:focus-visible,div#\:\$p>svg>foreignObject>section input[type=checkbox]:focus-visible,div#\:\$p>svg>foreignObject>section input[type=radio]:focus-visible{box-shadow:none;outline:2px solid var(--color-accent-fg);outline-offset:-2px}div#\:\$p>svg>foreignObject>section a:not([class]):focus,div#\:\$p>svg>foreignObject>section a:not([class]):focus-visible,div#\:\$p>svg>foreignObject>section input[type=checkbox]:focus,div#\:\$p>svg>foreignObject>section input[type=checkbox]:focus-visible,div#\:\$p>svg>foreignObject>section input[type=radio]:focus,div#\:\$p>svg>foreignObject>section input[type=radio]:focus-visible{outline-offset:0}div#\:\$p>svg>foreignObject>section kbd{background-color:var(--color-canvas-subtle);border-bottom-color:var(--color-neutral-muted);border:1px solid var(--color-neutral-muted);border-radius:6px;box-shadow:inset 0 -1px 0 var(--color-neutral-muted);color:var(--color-fg-default);display:inline-block;font:11px ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;line-height:10px;padding:3px 5px;vertical-align:middle}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1),div#\:\$p>svg>foreignObject>section :is(h2,marp-h2),div#\:\$p>svg>foreignObject>section :is(h3,marp-h3),div#\:\$p>svg>foreignObject>section :is(h4,marp-h4),div#\:\$p>svg>foreignObject>section :is(h5,marp-h5),div#\:\$p>svg>foreignObject>section :is(h6,marp-h6){font-weight:var(--base-text-weight-semibold,600);line-height:1.25;margin-bottom:16px;margin-top:24px}div#\:\$p>svg>foreignObject>section :is(h2,marp-h2){border-bottom:1px solid var(--color-border-muted);font-size:1.5em;padding-bottom:.3em}div#\:\$p>svg>foreignObject>section :is(h2,marp-h2),div#\:\$p>svg>foreignObject>section :is(h3,marp-h3){font-weight:var(--base-text-weight-semibold,600)}div#\:\$p>svg>foreignObject>section :is(h3,marp-h3){font-size:1.25em}div#\:\$p>svg>foreignObject>section :is(h4,marp-h4){font-size:1em}div#\:\$p>svg>foreignObject>section :is(h4,marp-h4),div#\:\$p>svg>foreignObject>section :is(h5,marp-h5){font-weight:var(--base-text-weight-semibold,600)}div#\:\$p>svg>foreignObject>section :is(h5,marp-h5){font-size:.875em}div#\:\$p>svg>foreignObject>section :is(h6,marp-h6){color:var(--color-fg-muted);font-size:.85em;font-weight:var(--base-text-weight-semibold,600)}div#\:\$p>svg>foreignObject>section p{margin-bottom:10px;margin-top:0}div#\:\$p>svg>foreignObject>section blockquote{border-left:.25em solid var(--color-border-default);color:var(--color-fg-muted);margin:0;padding:0 1em}div#\:\$p>svg>foreignObject>section ol,div#\:\$p>svg>foreignObject>section ul{margin-bottom:0;margin-top:0;padding-left:2em}div#\:\$p>svg>foreignObject>section ol ol,div#\:\$p>svg>foreignObject>section ul ol{list-style-type:lower-roman}div#\:\$p>svg>foreignObject>section ol ol ol,div#\:\$p>svg>foreignObject>section ol ul ol,div#\:\$p>svg>foreignObject>section ul ol ol,div#\:\$p>svg>foreignObject>section ul ul ol{list-style-type:lower-alpha}div#\:\$p>svg>foreignObject>section dd{margin-left:0}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre),div#\:\$p>svg>foreignObject>section code,div#\:\$p>svg>foreignObject>section samp,div#\:\$p>svg>foreignObject>section tt{font-family:ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;font-size:12px}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre){word-wrap:normal;margin-bottom:0;margin-top:0}div#\:\$p>svg>foreignObject>section .octicon{fill:currentColor;display:inline-block;overflow:visible!important;vertical-align:text-bottom}div#\:\$p>svg>foreignObject>section input::-webkit-inner-spin-button,div#\:\$p>svg>foreignObject>section input::-webkit-outer-spin-button{-webkit-appearance:none;appearance:none;margin:0}div#\:\$p>svg>foreignObject>section:after,div#\:\$p>svg>foreignObject>section:before{
  /* content:""; */display:table}div#\:\$p>svg>foreignObject>section:after{clear:both}div#\:\$p>svg>foreignObject>section>:first-child{margin-top:0!important}div#\:\$p>svg>foreignObject>section>:last-child{margin-bottom:0!important}div#\:\$p>svg>foreignObject>section a:not([href]){color:inherit;text-decoration:none}div#\:\$p>svg>foreignObject>section .absent{color:var(--color-danger-fg)}div#\:\$p>svg>foreignObject>section .anchor{float:left;line-height:1;margin-left:-20px;padding-right:4px}div#\:\$p>svg>foreignObject>section .anchor:focus{outline:none}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre),div#\:\$p>svg>foreignObject>section blockquote,div#\:\$p>svg>foreignObject>section details,div#\:\$p>svg>foreignObject>section dl,div#\:\$p>svg>foreignObject>section ol,div#\:\$p>svg>foreignObject>section p,div#\:\$p>svg>foreignObject>section table,div#\:\$p>svg>foreignObject>section ul{margin-bottom:16px;margin-top:0}div#\:\$p>svg>foreignObject>section blockquote>:first-child{margin-top:0}div#\:\$p>svg>foreignObject>section blockquote>:last-child{margin-bottom:0}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1) .octicon-link,div#\:\$p>svg>foreignObject>section :is(h2,marp-h2) .octicon-link,div#\:\$p>svg>foreignObject>section :is(h3,marp-h3) .octicon-link,div#\:\$p>svg>foreignObject>section :is(h4,marp-h4) .octicon-link,div#\:\$p>svg>foreignObject>section :is(h5,marp-h5) .octicon-link,div#\:\$p>svg>foreignObject>section :is(h6,marp-h6) .octicon-link{color:var(--color-fg-default);vertical-align:middle;visibility:hidden}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1):hover .anchor,div#\:\$p>svg>foreignObject>section :is(h2,marp-h2):hover .anchor,div#\:\$p>svg>foreignObject>section :is(h3,marp-h3):hover .anchor,div#\:\$p>svg>foreignObject>section :is(h4,marp-h4):hover .anchor,div#\:\$p>svg>foreignObject>section :is(h5,marp-h5):hover .anchor,div#\:\$p>svg>foreignObject>section :is(h6,marp-h6):hover .anchor{text-decoration:none}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1):hover .anchor .octicon-link,div#\:\$p>svg>foreignObject>section :is(h2,marp-h2):hover .anchor .octicon-link,div#\:\$p>svg>foreignObject>section :is(h3,marp-h3):hover .anchor .octicon-link,div#\:\$p>svg>foreignObject>section :is(h4,marp-h4):hover .anchor .octicon-link,div#\:\$p>svg>foreignObject>section :is(h5,marp-h5):hover .anchor .octicon-link,div#\:\$p>svg>foreignObject>section :is(h6,marp-h6):hover .anchor .octicon-link{visibility:visible}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1) code,div#\:\$p>svg>foreignObject>section :is(h1,marp-h1) tt,div#\:\$p>svg>foreignObject>section :is(h2,marp-h2) code,div#\:\$p>svg>foreignObject>section :is(h2,marp-h2) tt,div#\:\$p>svg>foreignObject>section :is(h3,marp-h3) code,div#\:\$p>svg>foreignObject>section :is(h3,marp-h3) tt,div#\:\$p>svg>foreignObject>section :is(h4,marp-h4) code,div#\:\$p>svg>foreignObject>section :is(h4,marp-h4) tt,div#\:\$p>svg>foreignObject>section :is(h5,marp-h5) code,div#\:\$p>svg>foreignObject>section :is(h5,marp-h5) tt,div#\:\$p>svg>foreignObject>section :is(h6,marp-h6) code,div#\:\$p>svg>foreignObject>section :is(h6,marp-h6) tt{font-size:inherit;padding:0 .2em}div#\:\$p>svg>foreignObject>section summary :is(h1,marp-h1),div#\:\$p>svg>foreignObject>section summary :is(h2,marp-h2),div#\:\$p>svg>foreignObject>section summary :is(h3,marp-h3),div#\:\$p>svg>foreignObject>section summary :is(h4,marp-h4),div#\:\$p>svg>foreignObject>section summary :is(h5,marp-h5),div#\:\$p>svg>foreignObject>section summary :is(h6,marp-h6){display:inline-block}div#\:\$p>svg>foreignObject>section summary :is(h1,marp-h1) .anchor,div#\:\$p>svg>foreignObject>section summary :is(h2,marp-h2) .anchor,div#\:\$p>svg>foreignObject>section summary :is(h3,marp-h3) .anchor,div#\:\$p>svg>foreignObject>section summary :is(h4,marp-h4) .anchor,div#\:\$p>svg>foreignObject>section summary :is(h5,marp-h5) .anchor,div#\:\$p>svg>foreignObject>section summary :is(h6,marp-h6) .anchor{margin-left:-40px}div#\:\$p>svg>foreignObject>section summary :is(h1,marp-h1),div#\:\$p>svg>foreignObject>section summary :is(h2,marp-h2){border-bottom:0;padding-bottom:0}div#\:\$p>svg>foreignObject>section ol.no-list,div#\:\$p>svg>foreignObject>section ul.no-list{list-style-type:none;padding:0}div#\:\$p>svg>foreignObject>section ol[type=a]{list-style-type:lower-alpha}div#\:\$p>svg>foreignObject>section ol[type=A]{list-style-type:upper-alpha}div#\:\$p>svg>foreignObject>section ol[type=i]{list-style-type:lower-roman}div#\:\$p>svg>foreignObject>section ol[type=I]{list-style-type:upper-roman}div#\:\$p>svg>foreignObject>section div>ol:not([type]),div#\:\$p>svg>foreignObject>section ol[type="1"]{list-style-type:decimal}div#\:\$p>svg>foreignObject>section ol ol,div#\:\$p>svg>foreignObject>section ol ul,div#\:\$p>svg>foreignObject>section ul ol,div#\:\$p>svg>foreignObject>section ul ul{margin-bottom:0;margin-top:0}div#\:\$p>svg>foreignObject>section li>p{margin-top:16px}div#\:\$p>svg>foreignObject>section li+li{margin-top:.25em}div#\:\$p>svg>foreignObject>section dl{padding:0}div#\:\$p>svg>foreignObject>section dl dt{font-size:1em;font-style:italic;font-weight:var(--base-text-weight-semibold,600);margin-top:16px;padding:0}div#\:\$p>svg>foreignObject>section dl dd{margin-bottom:16px;padding:0 16px}div#\:\$p>svg>foreignObject>section table th{font-weight:var(--base-text-weight-semibold,600)}div#\:\$p>svg>foreignObject>section table td,div#\:\$p>svg>foreignObject>section table th{border:1px solid var(--color-border-default);padding:6px 13px}div#\:\$p>svg>foreignObject>section table tr{background-color:var(--color-canvas-default);border-top:1px solid var(--color-border-muted)}div#\:\$p>svg>foreignObject>section table tr:nth-child(2n){background-color:var(--color-canvas-subtle)}div#\:\$p>svg>foreignObject>section table img{background-color:transparent}div#\:\$p>svg>foreignObject>section img[align=right]{padding-left:20px}div#\:\$p>svg>foreignObject>section img[align=left]{padding-right:20px}div#\:\$p>svg>foreignObject>section .emoji{background-color:transparent;max-width:none;vertical-align:text-top}div#\:\$p>svg>foreignObject>section :is(span,marp-span).frame,div#\:\$p>svg>foreignObject>section :is(span,marp-span).frame>:is(span,marp-span){display:block;overflow:hidden}div#\:\$p>svg>foreignObject>section :is(span,marp-span).frame>:is(span,marp-span){border:1px solid var(--color-border-default);float:left;margin:13px 0 0;padding:7px;width:auto}div#\:\$p>svg>foreignObject>section :is(span,marp-span).frame :is(span,marp-span) img{display:block;float:left}div#\:\$p>svg>foreignObject>section :is(span,marp-span).frame :is(span,marp-span) :is(span,marp-span){clear:both;color:var(--color-fg-default);display:block;padding:5px 0 0}div#\:\$p>svg>foreignObject>section :is(span,marp-span).align-center{clear:both;display:block;overflow:hidden}div#\:\$p>svg>foreignObject>section :is(span,marp-span).align-center>:is(span,marp-span){display:block;margin:13px auto 0;overflow:hidden;text-align:center}div#\:\$p>svg>foreignObject>section :is(span,marp-span).align-center :is(span,marp-span) img{margin:0 auto;text-align:center}div#\:\$p>svg>foreignObject>section :is(span,marp-span).align-right{clear:both;display:block;overflow:hidden}div#\:\$p>svg>foreignObject>section :is(span,marp-span).align-right>:is(span,marp-span){display:block;margin:13px 0 0;overflow:hidden;text-align:right}div#\:\$p>svg>foreignObject>section :is(span,marp-span).align-right :is(span,marp-span) img{margin:0;text-align:right}div#\:\$p>svg>foreignObject>section :is(span,marp-span).float-left{display:block;float:left;margin-right:13px;overflow:hidden}div#\:\$p>svg>foreignObject>section :is(span,marp-span).float-left :is(span,marp-span){margin:13px 0 0}div#\:\$p>svg>foreignObject>section :is(span,marp-span).float-right{display:block;float:right;margin-left:13px;overflow:hidden}div#\:\$p>svg>foreignObject>section :is(span,marp-span).float-right>:is(span,marp-span){display:block;margin:13px auto 0;overflow:hidden;text-align:right}div#\:\$p>svg>foreignObject>section code,div#\:\$p>svg>foreignObject>section tt{background-color:var(--color-neutral-muted);border-radius:6px;font-size:85%;margin:0;padding:.2em .4em;white-space:break-spaces}div#\:\$p>svg>foreignObject>section code br,div#\:\$p>svg>foreignObject>section tt br{display:none}div#\:\$p>svg>foreignObject>section del code{text-decoration:inherit}div#\:\$p>svg>foreignObject>section samp{font-size:85%}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) code{font-size:100%}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre)>code{background:transparent;border:0;margin:0;padding:0;white-space:pre;word-break:normal}div#\:\$p>svg>foreignObject>section .highlight{margin-bottom:16px}div#\:\$p>svg>foreignObject>section .highlight :is(pre,marp-pre){margin-bottom:0;word-break:normal}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre){background-color:var(--color-canvas-subtle);border-radius:6px;font-size:85%;line-height:1.45;overflow:auto;padding:16px}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) code,div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) tt{word-wrap:normal;background-color:transparent;border:0;display:inline;line-height:inherit;margin:0;max-width:auto;overflow:visible;padding:0}div#\:\$p>svg>foreignObject>section .csv-data td,div#\:\$p>svg>foreignObject>section .csv-data th{font-size:12px;line-height:1;overflow:hidden;padding:5px;text-align:left;white-space:nowrap}div#\:\$p>svg>foreignObject>section .csv-data .blob-num{background:var(--color-canvas-default);border:0;padding:10px 8px 9px;text-align:right}div#\:\$p>svg>foreignObject>section .csv-data tr{border-top:0}div#\:\$p>svg>foreignObject>section .csv-data th{background:var(--color-canvas-subtle);border-top:0;font-weight:var(--base-text-weight-semibold,600)}div#\:\$p>svg>foreignObject>section [data-footnote-ref]:before{content:"["}div#\:\$p>svg>foreignObject>section [data-footnote-ref]:after{content:"]"}div#\:\$p>svg>foreignObject>section .footnotes{border-top:1px solid var(--color-border-default);color:var(--color-fg-muted);font-size:12px}div#\:\$p>svg>foreignObject>section div#\:\$p>svg>foreignObject>section section.footnotes{--marpit-root-font-size:12px}div#\:\$p>svg>foreignObject>section .footnotes ol{padding-left:16px}div#\:\$p>svg>foreignObject>section .footnotes ol ul{display:inline-block;margin-top:16px;padding-left:16px}div#\:\$p>svg>foreignObject>section .footnotes li{position:relative}div#\:\$p>svg>foreignObject>section .footnotes li:target:before{border:2px solid var(--color-accent-emphasis);border-radius:6px;bottom:-8px;content:"";left:-24px;pointer-events:none;position:absolute;right:-8px;top:-8px}div#\:\$p>svg>foreignObject>section .footnotes li:target{color:var(--color-fg-default)}div#\:\$p>svg>foreignObject>section .footnotes .data-footnote-backref g-emoji{font-family:monospace}div#\:\$p>svg>foreignObject>section .pl-c{color:var(--color-prettylights-syntax-comment)}div#\:\$p>svg>foreignObject>section .pl-c1,div#\:\$p>svg>foreignObject>section .pl-s .pl-v{color:var(--color-prettylights-syntax-constant)}div#\:\$p>svg>foreignObject>section .pl-e,div#\:\$p>svg>foreignObject>section .pl-en{color:var(--color-prettylights-syntax-entity)}div#\:\$p>svg>foreignObject>section .pl-s .pl-s1,div#\:\$p>svg>foreignObject>section .pl-smi{color:var(--color-prettylights-syntax-storage-modifier-import)}div#\:\$p>svg>foreignObject>section .pl-ent{color:var(--color-prettylights-syntax-entity-tag)}div#\:\$p>svg>foreignObject>section .pl-k{color:var(--color-prettylights-syntax-keyword)}div#\:\$p>svg>foreignObject>section .pl-pds,div#\:\$p>svg>foreignObject>section .pl-s,div#\:\$p>svg>foreignObject>section .pl-s .pl-pse .pl-s1,div#\:\$p>svg>foreignObject>section .pl-sr,div#\:\$p>svg>foreignObject>section .pl-sr .pl-cce,div#\:\$p>svg>foreignObject>section .pl-sr .pl-sra,div#\:\$p>svg>foreignObject>section .pl-sr .pl-sre{color:var(--color-prettylights-syntax-string)}div#\:\$p>svg>foreignObject>section .pl-smw,div#\:\$p>svg>foreignObject>section .pl-v{color:var(--color-prettylights-syntax-variable)}div#\:\$p>svg>foreignObject>section .pl-bu{color:var(--color-prettylights-syntax-brackethighlighter-unmatched)}div#\:\$p>svg>foreignObject>section .pl-ii{background-color:var(--color-prettylights-syntax-invalid-illegal-bg);color:var(--color-prettylights-syntax-invalid-illegal-text)}div#\:\$p>svg>foreignObject>section .pl-c2{background-color:var(--color-prettylights-syntax-carriage-return-bg);color:var(--color-prettylights-syntax-carriage-return-text)}div#\:\$p>svg>foreignObject>section .pl-sr .pl-cce{color:var(--color-prettylights-syntax-string-regexp);font-weight:700}div#\:\$p>svg>foreignObject>section .pl-ml{color:var(--color-prettylights-syntax-markup-list)}div#\:\$p>svg>foreignObject>section .pl-mh,div#\:\$p>svg>foreignObject>section .pl-mh .pl-en,div#\:\$p>svg>foreignObject>section .pl-ms{color:var(--color-prettylights-syntax-markup-heading);font-weight:700}div#\:\$p>svg>foreignObject>section .pl-mi{color:var(--color-prettylights-syntax-markup-italic);font-style:italic}div#\:\$p>svg>foreignObject>section .pl-mb{color:var(--color-prettylights-syntax-markup-bold);font-weight:700}div#\:\$p>svg>foreignObject>section .pl-md{background-color:var(--color-prettylights-syntax-markup-deleted-bg);color:var(--color-prettylights-syntax-markup-deleted-text)}div#\:\$p>svg>foreignObject>section .pl-mi1{background-color:var(--color-prettylights-syntax-markup-inserted-bg);color:var(--color-prettylights-syntax-markup-inserted-text)}div#\:\$p>svg>foreignObject>section .pl-mc{background-color:var(--color-prettylights-syntax-markup-changed-bg);color:var(--color-prettylights-syntax-markup-changed-text)}div#\:\$p>svg>foreignObject>section .pl-mi2{background-color:var(--color-prettylights-syntax-markup-ignored-bg);color:var(--color-prettylights-syntax-markup-ignored-text)}div#\:\$p>svg>foreignObject>section .pl-mdr{color:var(--color-prettylights-syntax-meta-diff-range);font-weight:700}div#\:\$p>svg>foreignObject>section .pl-ba{color:var(--color-prettylights-syntax-brackethighlighter-angle)}div#\:\$p>svg>foreignObject>section .pl-sg{color:var(--color-prettylights-syntax-sublimelinter-gutter-mark)}div#\:\$p>svg>foreignObject>section .pl-corl{color:var(--color-prettylights-syntax-constant-other-reference-link);text-decoration:underline}div#\:\$p>svg>foreignObject>section g-emoji{display:inline-block;font-family:Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol;font-size:1em;font-style:normal!important;font-weight:var(--base-text-weight-normal,400);line-height:1;min-width:1ch;vertical-align:-.075em}div#\:\$p>svg>foreignObject>section g-emoji img{height:1em;width:1em}div#\:\$p>svg>foreignObject>section .task-list-item{list-style-type:none}div#\:\$p>svg>foreignObject>section .task-list-item label{font-weight:var(--base-text-weight-normal,400)}div#\:\$p>svg>foreignObject>section .task-list-item.enabled label{cursor:pointer}div#\:\$p>svg>foreignObject>section .task-list-item+.task-list-item{margin-top:4px}div#\:\$p>svg>foreignObject>section .task-list-item .handle{display:none}div#\:\$p>svg>foreignObject>section .task-list-item-checkbox{margin:0 .2em .25em -1.4em;vertical-align:middle}div#\:\$p>svg>foreignObject>section .contains-task-list:dir(rtl) .task-list-item-checkbox{margin:0 -1.6em .25em .2em}div#\:\$p>svg>foreignObject>section .contains-task-list{position:relative}div#\:\$p>svg>foreignObject>section .contains-task-list:focus-within .task-list-item-convert-container,div#\:\$p>svg>foreignObject>section .contains-task-list:hover .task-list-item-convert-container{clip:auto;display:block;height:24px;overflow:visible;width:auto}div#\:\$p>svg>foreignObject>section ::-webkit-calendar-picker-indicator{filter:invert(50%)}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1){color:var(--h1-color);font-size:1.6em}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1),div#\:\$p>svg>foreignObject>section :is(h2,marp-h2){border-bottom:none}div#\:\$p>svg>foreignObject>section :is(h2,marp-h2){font-size:1.3em}div#\:\$p>svg>foreignObject>section :is(h3,marp-h3){font-size:1.1em}div#\:\$p>svg>foreignObject>section :is(h4,marp-h4){font-size:1.05em}div#\:\$p>svg>foreignObject>section :is(h5,marp-h5){font-size:1em}div#\:\$p>svg>foreignObject>section :is(h6,marp-h6){font-size:.9em}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1) strong,div#\:\$p>svg>foreignObject>section :is(h2,marp-h2) strong,div#\:\$p>svg>foreignObject>section :is(h3,marp-h3) strong,div#\:\$p>svg>foreignObject>section :is(h4,marp-h4) strong,div#\:\$p>svg>foreignObject>section :is(h5,marp-h5) strong,div#\:\$p>svg>foreignObject>section :is(h6,marp-h6) strong{color:var(--heading-strong-color);font-weight:inherit}div#\:\$p>svg>foreignObject>section :is(h1,marp-h1)::part(auto-scaling),div#\:\$p>svg>foreignObject>section :is(h2,marp-h2)::part(auto-scaling),div#\:\$p>svg>foreignObject>section :is(h3,marp-h3)::part(auto-scaling),div#\:\$p>svg>foreignObject>section :is(h4,marp-h4)::part(auto-scaling),div#\:\$p>svg>foreignObject>section :is(h5,marp-h5)::part(auto-scaling),div#\:\$p>svg>foreignObject>section :is(h6,marp-h6)::part(auto-scaling){max-height:563px}div#\:\$p>svg>foreignObject>section hr{height:0;padding-top:.25em}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre){border:1px solid var(--color-border-default);line-height:1.15;overflow:visible}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre)::part(auto-scaling){max-height:529px}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs){color:var(--color-prettylights-syntax-storage-modifier-import)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-doctag),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-keyword),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-meta .hljs-keyword),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-template-tag),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-template-variable),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-type),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-variable.language_){color:var(--color-prettylights-syntax-keyword)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-title),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-title.class_),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-title.class_.inherited__),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-title.function_){color:var(--color-prettylights-syntax-entity)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-attr),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-attribute),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-literal),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-meta),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-number),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-operator),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-selector-attr),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-selector-class),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-selector-id),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-variable){color:var(--color-prettylights-syntax-constant)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-meta .hljs-string),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-regexp),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-string){color:var(--color-prettylights-syntax-string)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-built_in),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-symbol){color:var(--color-prettylights-syntax-variable)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-code),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-comment),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-formula){color:var(--color-prettylights-syntax-comment)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-name),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-quote),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-selector-pseudo),div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-selector-tag){color:var(--color-prettylights-syntax-entity-tag)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-subst){color:var(--color-prettylights-syntax-storage-modifier-import)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-section){color:var(--color-prettylights-syntax-markup-heading);font-weight:700}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-bullet){color:var(--color-prettylights-syntax-markup-list)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-emphasis){color:var(--color-prettylights-syntax-markup-italic);font-style:italic}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-strong){color:var(--color-prettylights-syntax-markup-bold);font-weight:700}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-addition){background-color:var(--color-prettylights-syntax-markup-inserted-bg);color:var(--color-prettylights-syntax-markup-inserted-text)}div#\:\$p>svg>foreignObject>section :is(pre,marp-pre) :where(.hljs-deletion){background-color:var(--color-prettylights-syntax-markup-deleted-bg);color:var(--color-prettylights-syntax-markup-deleted-text)}div#\:\$p>svg>foreignObject>section footer,div#\:\$p>svg>foreignObject>section header{color:var(--header-footer-color);font-size:18px;left:30px;margin:0;position:absolute}div#\:\$p>svg>foreignObject>section header{top:21px}div#\:\$p>svg>foreignObject>section footer{bottom:21px}div#\:\$p>svg>foreignObject>section{--h1-color:#246;--header-footer-color:hsla(0,0%,40%,.75);--heading-strong-color:#48c;--paginate-color:#777;align-items:stretch;display:flex;flex-flow:column nowrap;font-size:29px;height:720px;justify-content:center;padding:78.5px;width:1280px}div#\:\$p>svg>foreignObject>section{--marpit-root-font-size:29px}div#\:\$p>svg>foreignObject>section:where(.invert){--h1-color:#cee7ff;--header-footer-color:hsla(0,0%,60%,.75);--heading-strong-color:#7bf;--paginate-color:#999}div#\:\$p>svg>foreignObject>section>:last-child,div#\:\$p>svg>foreignObject>section[data-footer]>:nth-last-child(2){margin-bottom:0}div#\:\$p>svg>foreignObject>section>:first-child,div#\:\$p>svg>foreignObject>section>header:first-child+*{margin-top:0}div#\:\$p>svg>foreignObject>section:after{bottom:21px;color:var(--paginate-color);font-size:24px;padding:0;position:absolute;right:30px}div#\:\$p>svg>foreignObject>section:after{--marpit-root-font-size:24px}div#\:\$p>svg>foreignObject>section[data-color] :is(h1,marp-h1),div#\:\$p>svg>foreignObject>section[data-color] :is(h2,marp-h2),div#\:\$p>svg>foreignObject>section[data-color] :is(h3,marp-h3),div#\:\$p>svg>foreignObject>section[data-color] :is(h4,marp-h4),div#\:\$p>svg>foreignObject>section[data-color] :is(h5,marp-h5),div#\:\$p>svg>foreignObject>section[data-color] :is(h6,marp-h6){color:currentcolor}div#\:\$p>svg>foreignObject>section{width:1280px;height:720px}div#\:\$p>svg>foreignObject>section .columns{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:calc(var(--marpit-root-font-size, 1rem) * 1)}div#\:\$p>svg>foreignObject>section{font-size:1.2em;justify-content:flex-start}div#\:\$p>svg>foreignObject>section{--marpit-root-font-size:1.2em}div#\:\$p>svg>foreignObject>section:after{font-size:0.6em;text-shadow:1px 1px 0 #fff;left:50%;transform:translateX(-50%);content:'[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'}div#\:\$p>svg>foreignObject>section:after{--marpit-root-font-size:0.6em}div#\:\$p>svg>foreignObject>section footer{bottom:10px}div#\:\$p>svg>foreignObject>section blockquote{border-top:0.1em dashed #555;font-size:60%;margin-top:50px}div#\:\$p>svg>foreignObject>section sup{font-size:65%}div#\:\$p>svg>foreignObject>section code{font-size:75%}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background]{columns:initial!important;display:block!important;padding:0!important}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background]:after,div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background]:before,div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=content]:after,div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=content]:before{display:none!important}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background]>div[data-marpit-advanced-background-container]{all:initial;display:flex;flex-direction:row;height:100%;overflow:hidden;width:100%}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background]>div[data-marpit-advanced-background-container][data-marpit-advanced-background-direction=vertical]{flex-direction:column}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background][data-marpit-advanced-background-split]>div[data-marpit-advanced-background-container]{width:var(--marpit-advanced-background-split,50%)}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background][data-marpit-advanced-background-split=right]>div[data-marpit-advanced-background-container]{margin-left:calc(100% - var(--marpit-advanced-background-split, 50%))}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=background]>div[data-marpit-advanced-background-container]>figure{all:initial;background-position:center;background-repeat:no-repeat;background-size:cover;flex:auto;margin:0}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=content],div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=pseudo]{background:transparent!important}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background=pseudo],div#\:\$p>svg[data-marpit-svg]>foreignObject[data-marpit-advanced-background=pseudo]{pointer-events:none!important}div#\:\$p>svg>foreignObject>section[data-marpit-advanced-background-split]{width:100%;height:100%}</style></head><body><div class="bespoke-marp-osc"><button data-bespoke-marp-osc="prev" tabindex="-1" title="Previous slide">Previous slide</button><span data-bespoke-marp-osc="page"></span><button data-bespoke-marp-osc="next" tabindex="-1" title="Next slide">Next slide</button><button data-bespoke-marp-osc="fullscreen" tabindex="-1" title="Toggle fullscreen (f)">Toggle fullscreen</button><button data-bespoke-marp-osc="presenter" tabindex="-1" title="Open presenter view (p)">Open presenter view</button></div><div id=":$p"><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="1" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h1 id="wright-laboratory-bootcamp"><strong>Wright Laboratory Bootcamp</strong></h1>
<h2 id="a-quick-introduction-to-remote-access-and-the-unix-command-line">A Quick Introduction to Remote Access and the Unix Command Line</h2>
<p>Vincent Balbarin<br />
June 8, 2023</p>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="2" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="2" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h2 id="remote-access">Remote Access</h2>
<p>Some of your computation will be done on remote, multi-user Linux environments such as rubin.physics.yale.edu, meitner.wlab.yale.edu, or the <code>grace</code> HPC computing cluster.</p>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="3" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="3" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h2 id="secure-shell-ssh">Secure Shell (SSH)</h2>
<p>The Secure Shell client enables you to authenticate and open an encrypted connection to a remote host.<br />
It allows for both username/password and key-based authentication.</p>
<p>The Wright Laboratory and YCRC HPC systems require the use of SSH keys for authentication.</p>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="4" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="4" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h2 id="create-a-new-ssh-key-pair">Create a New SSH Key Pair</h2>
<p>Launching a command line terminal:</p>
<ol>
<li>Mac OS
<ol>
<li>Bring up Spotlight: [⌘] command + [space]</li>
<li>Type <strong>Terminal</strong> and press [return] return to launch the Terminal app.</li>
</ol>
</li>
<li>Windows
<ol>
<li>Begin search by pressing [❖] Win</li>
<li>Type <strong>Powershell</strong></li>
<li>Highlight <strong>Powershell</strong> in search results and press [⌤] enter to launch.</li>
</ol>
</li>
</ol>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="5" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="5" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<p>Generation of SSH keypair:</p>
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-shell">ssh-keygen --type ed25519
</code></pre>
<ol>
<li>Answer the prompts with default values.</li>
<li>It is strongly recommended to use a password to protect your private key.</li>
<li>Once a key pair has been generated, the private and public key will be found at <code>${HOME}/.ssh</code> (Mac OS, Linux) or <code>${Env:USERPROFILE}\.ssh</code> (Windows)</li>
</ol>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="6" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="6" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<p>Display the public key</p>
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-bash"><span class="hljs-built_in">cat</span> <span class="hljs-variable">${HOME}</span>/.ssh/id_ed25519.pub | pbcopy
</code></pre>
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-powershell"><span class="hljs-built_in">gc</span> <span class="hljs-literal">-Path</span> <span class="hljs-string">&quot;<span class="hljs-variable">$</span>{env:USERPROFILE}\.ssh\id_ed25519.pub&quot;</span> | <span class="hljs-built_in">Set-Clipboard</span>
</code></pre>
<ol>
<li>Paste that value into an email to me with your NetID, preferred first and last name, and your PI.</li>
<li>This public key will be installed to your account home folder on the remote system.</li>
</ol>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="7" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="7" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<p>To create a remote session, open a command line session and type:</p>
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-shell">ssh -i ./ssh/id_ed25519.pub {{ NetID }}@{{ HostFQDN }}
</code></pre>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="8" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="8" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h2 id="the-shell">The Shell</h2>
<p>The shell is a text-based environment that lets you interact with the computer.<br />
Windows has two native shells.</p>
<p>There are several different shells available on Linux and other variants of Unix such as Mac OS.</p>
<p>We will focus on Bash.<br />
(Mac OS currently uses a related shell Zsh.)</p>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="9" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="9" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h2 id="navigating-the-file-system">Navigating the File System</h2>
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-bash"><span class="hljs-comment"># Display (print) your current working directory</span>
<span class="hljs-built_in">pwd</span>

<span class="hljs-comment"># Change directory</span>
<span class="hljs-built_in">cd</span> /path/to/directory

<span class="hljs-comment"># Change directory, stash path of current working directory</span>
<span class="hljs-built_in">pushd</span> /path/to/directory
<span class="hljs-comment"># Perform actions</span>
<span class="hljs-comment"># Return to original working directory</span>
<span class="hljs-built_in">popd</span>

<span class="hljs-comment"># List the contents of your current directory</span>
<span class="hljs-built_in">ls</span> -la
total 32
drwx------. 3 netid netid    95 Jun  7 19:10 .
drwxr-xr-x. 5 root root      51 May 12 20:53 ..
-rw-------. 1 netid netid 18713 Jun  7 16:53 .bash_history
-rw-r--r--. 1 netid netid    18 Aug  3  2022 .bash_logout
-rw-r--r--. 1 netid netid   141 Aug  3  2022 .bash_profile
-rw-r--r--. 1 netid netid   853 Jun  2 14:21 .bashrc
drwx------. 2 netid netid    29 Jun  3 14:40 .ssh
</code></pre>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="10" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="10" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h2 id="working-with-files-and-folders">Working with Files and Folders</h2>
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-bash"><span class="hljs-comment"># Print text to the screen</span>
<span class="hljs-built_in">echo</span> <span class="hljs-string">&quot;Hello, World!&quot;</span>

<span class="hljs-comment"># Redirect to a file</span>
<span class="hljs-built_in">echo</span> <span class="hljs-string">&quot;0 meow&quot;</span> &gt; box.txt

<span class="hljs-comment"># Append to existing file</span>
<span class="hljs-built_in">echo</span> <span class="hljs-string">&quot;1 meow&quot;</span> &gt;&gt; box.txt

<span class="hljs-comment"># Repeat 998 more times, starting from 2</span>
<span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> {2..1000}; <span class="hljs-keyword">do</span> <span class="hljs-built_in">echo</span> <span class="hljs-string">&quot;<span class="hljs-variable">${i}</span> meow&quot;</span> &gt;&gt; box.txt; <span class="hljs-keyword">done</span>

<span class="hljs-comment"># Display contents, pausing output</span>
<span class="hljs-built_in">cat</span> box.txt | less

<span class="hljs-comment"># Delete file</span>
<span class="hljs-built_in">rm</span> box.txt

<span class="hljs-comment"># Copy a file</span>
<span class="hljs-built_in">cp</span> <span class="hljs-string">&quot;/path/to/source/file&quot;</span> <span class="hljs-string">&quot;/path/to/destination/file&quot;</span>

<span class="hljs-comment"># Move a file</span>
<span class="hljs-built_in">mv</span> <span class="hljs-string">&quot;/path/to/source/file&quot;</span> <span class="hljs-string">&quot;/path/to/destination/file&quot;</span>
<span class="hljs-comment"># Can also be used to rename a file</span>
<span class="hljs-built_in">mv</span> <span class="hljs-string">&quot;file.txt&quot;</span> <span class="hljs-string">&quot;file.bak&quot;</span>

<span class="hljs-comment"># Edit a text file</span>
nano <span class="hljs-string">&quot;/path/to/file&quot;</span>
</code></pre>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="11" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="11" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-bash"><span class="hljs-comment"># Create a new folder</span>
<span class="hljs-built_in">mkdir</span> -p /path/to/new/folder

<span class="hljs-comment"># Remove a folder and all its contents</span>
<span class="hljs-built_in">rm</span> -R /path/to/folder/*

<span class="hljs-comment"># Copy a folder</span>
<span class="hljs-built_in">cp</span> -R /path/to/folder /path/to/folder_bak

<span class="hljs-comment"># Remove the contents of a folder, leaving subfolders intact</span>
<span class="hljs-comment"># Note remove `echo` to actually delete files</span>
find ./ -<span class="hljs-built_in">type</span> f -name <span class="hljs-string">&quot;*&quot;</span> -print0 | xargs -0 -I <span class="hljs-string">&#x27;%&#x27;</span> bash -c <span class="hljs-string">&#x27;echo rm &quot;%&quot;&#x27;</span>
find ./ -<span class="hljs-built_in">type</span> f -name <span class="hljs-string">&quot;*&quot;</span>  -execdir bash -c <span class="hljs-string">&#x27;echo rm &quot;{}&quot;&#x27;</span> \;


</code></pre>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
</foreignObject></svg><svg data-marpit-svg="" viewBox="0 0 1280 720"><foreignObject width="1280" height="720"><section id="12" data-background-color="#fff" data-footer="![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)" data-paginate="true" data-theme="default" data-style=".columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
" data-marpit-pagination="12" data-marpit-pagination-total="12" style="--background-color:#fff;--footer:![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png);--paginate:true;--theme:default;--style:.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}

section {
  font-size: 1.2em;
  justify-content: flex-start;
}

section::after {
  font-size: 0.6em;
  text-shadow: 1px 1px 0 #fff;
  left: 50%;
  transform: translateX(-50%);
  content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
} 

footer {
  bottom: 10px
}
;background-color:#fff;background-image:none;" data-size="16:9">
<h2 id="information-help-and-hints">Information, Help, and Hints</h2>
<pre is="marp-pre" data-auto-scaling="downscale-only"><code class="language-bash"><span class="hljs-comment"># List all of your current shell&#x27;s environment variables</span>
<span class="hljs-comment"># available to running applications/processes in your shell</span>
<span class="hljs-built_in">env</span>

<span class="hljs-comment"># You may use the value of any variable in a command by using ${VARIABLE_NAME}</span>
<span class="hljs-built_in">echo</span> <span class="hljs-string">&quot;<span class="hljs-variable">${PATH}</span>&quot;</span>

<span class="hljs-comment"># Getting manual pages on a particular installed command</span>
man <span class="hljs-string">&quot;{{ command }}&quot;</span>

<span class="hljs-comment"># Quick query for command, returns the name field of the manual pages</span>
whatis <span class="hljs-string">&quot;{{ command }}&quot;</span>

<span class="hljs-comment"># Query for command or action in both name and description fields of all manual pages</span>
<span class="hljs-comment"># When you have an idea of what you want, but not a specific command</span>
apropos <span class="hljs-string">&quot;{{ commandOrAction }}&quot;</span>
</code></pre>
<footer><img src="https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png" alt="wl_footer" /></footer>
</section>
<script>!function(){"use strict";const t={h1:{proto:()=>HTMLHeadingElement,attrs:{role:"heading","aria-level":"1"},style:"display: block; font-size: 2em; margin-block-start: 0.67em; margin-block-end: 0.67em; margin-inline-start: 0px; margin-inline-end: 0px; font-weight: bold;"},h2:{proto:()=>HTMLHeadingElement,attrs:{role:"heading","aria-level":"2"},style:"display: block; font-size: 1.5em; margin-block-start: 0.83em; margin-block-end: 0.83em; margin-inline-start: 0px; margin-inline-end: 0px; font-weight: bold;"},h3:{proto:()=>HTMLHeadingElement,attrs:{role:"heading","aria-level":"3"},style:"display: block; font-size: 1.17em; margin-block-start: 1em; margin-block-end: 1em; margin-inline-start: 0px; margin-inline-end: 0px; font-weight: bold;"},h4:{proto:()=>HTMLHeadingElement,attrs:{role:"heading","aria-level":"4"},style:"display: block; margin-block-start: 1.33em; margin-block-end: 1.33em; margin-inline-start: 0px; margin-inline-end: 0px; font-weight: bold;"},h5:{proto:()=>HTMLHeadingElement,attrs:{role:"heading","aria-level":"5"},style:"display: block; font-size: 0.83em; margin-block-start: 1.67em; margin-block-end: 1.67em; margin-inline-start: 0px; margin-inline-end: 0px; font-weight: bold;"},h6:{proto:()=>HTMLHeadingElement,attrs:{role:"heading","aria-level":"6"},style:"display: block; font-size: 0.67em; margin-block-start: 2.33em; margin-block-end: 2.33em; margin-inline-start: 0px; margin-inline-end: 0px; font-weight: bold;"},span:{proto:()=>HTMLSpanElement},pre:{proto:()=>HTMLElement,style:"display: block; font-family: monospace; white-space: pre; margin: 1em 0; --marp-auto-scaling-white-space: pre;"}},e="data-marp-auto-scaling-wrapper",i="data-marp-auto-scaling-svg",n="data-marp-auto-scaling-container";class s extends HTMLElement{constructor(){super(),this.svgPreserveAspectRatio="xMinYMid meet";const t=t=>([e])=>{const{width:i,height:n}=e.contentRect;this[t]={width:i,height:n},this.updateSVGRect()};this.attachShadow({mode:"open"}),this.containerObserver=new ResizeObserver(t("containerSize")),this.wrapperObserver=new ResizeObserver(((...e)=>{t("wrapperSize")(...e),this.flushSvgDisplay()}))}static get observedAttributes(){return["data-downscale-only"]}connectedCallback(){var t,s,o,r,a;this.shadowRoot.innerHTML=`\n<style>\n  svg[${i}] { display: block; width: 100%; height: auto; vertical-align: top; }\n  span[${n}] { display: table; white-space: var(--marp-auto-scaling-white-space, nowrap); width: max-content; }\n</style>\n<div ${e}>\n  <svg part="svg" ${i}>\n    <foreignObject><span ${n}><slot></slot></span></foreignObject>\n  </svg>\n</div>\n    `.split(/\n\s*/).join(""),this.wrapper=null!==(t=this.shadowRoot.querySelector(`div[${e}]`))&&void 0!==t?t:void 0;const l=this.svg;this.svg=null!==(o=null===(s=this.wrapper)||void 0===s?void 0:s.querySelector(`svg[${i}]`))&&void 0!==o?o:void 0,this.svg!==l&&(this.svgComputedStyle=this.svg?window.getComputedStyle(this.svg):void 0),this.container=null!==(a=null===(r=this.svg)||void 0===r?void 0:r.querySelector(`span[${n}]`))&&void 0!==a?a:void 0,this.observe()}disconnectedCallback(){this.svg=void 0,this.svgComputedStyle=void 0,this.wrapper=void 0,this.container=void 0,this.observe()}attributeChangedCallback(){this.observe()}flushSvgDisplay(){const{svg:t}=this;t&&(t.style.display="inline",requestAnimationFrame((()=>{t.style.display=""})))}observe(){this.containerObserver.disconnect(),this.wrapperObserver.disconnect(),this.wrapper&&this.wrapperObserver.observe(this.wrapper),this.container&&this.containerObserver.observe(this.container),this.svgComputedStyle&&this.observeSVGStyle(this.svgComputedStyle)}observeSVGStyle(t){const e=()=>{const i=(()=>{const e=t.getPropertyValue("--preserve-aspect-ratio");if(e)return e.trim();return`x${(({textAlign:t,direction:e})=>{if(t.endsWith("left"))return"Min";if(t.endsWith("right"))return"Max";if("start"===t||"end"===t){let i="rtl"===e;return"end"===t&&(i=!i),i?"Max":"Min"}return"Mid"})(t)}YMid meet`})();i!==this.svgPreserveAspectRatio&&(this.svgPreserveAspectRatio=i,this.updateSVGRect()),t===this.svgComputedStyle&&requestAnimationFrame(e)};e()}updateSVGRect(){var t,e,i,n,s,o,r;let a=Math.ceil(null!==(e=null===(t=this.containerSize)||void 0===t?void 0:t.width)&&void 0!==e?e:0);const l=Math.ceil(null!==(n=null===(i=this.containerSize)||void 0===i?void 0:i.height)&&void 0!==n?n:0);void 0!==this.dataset.downscaleOnly&&(a=Math.max(a,null!==(o=null===(s=this.wrapperSize)||void 0===s?void 0:s.width)&&void 0!==o?o:0));const c=null===(r=this.svg)||void 0===r?void 0:r.querySelector(":scope > foreignObject");if(null==c||c.setAttribute("width",`${a}`),null==c||c.setAttribute("height",`${l}`),this.svg&&(this.svg.setAttribute("viewBox",`0 0 ${a} ${l}`),this.svg.setAttribute("preserveAspectRatio",this.svgPreserveAspectRatio),this.svg.style.height=a<=0||l<=0?"0":""),this.container){const t=this.svgPreserveAspectRatio.toLowerCase();this.container.style.marginLeft=t.startsWith("xmid")||t.startsWith("xmax")?"auto":"0",this.container.style.marginRight=t.startsWith("xmi")?"auto":"0"}}}const o=(t,{attrs:e={},style:i})=>class extends t{constructor(...t){super(...t);for(const[t,i]of Object.entries(e))this.hasAttribute(t)||this.setAttribute(t,i);this.attachShadow({mode:"open"})}static get observedAttributes(){return["data-auto-scaling"]}connectedCallback(){this._update()}attributeChangedCallback(){this._update()}_update(){const t=i?`<style>:host { ${i} }</style>`:"";let e="<slot></slot>";const{autoScaling:n}=this.dataset;if(void 0!==n){e=`<marp-auto-scaling exportparts="svg:auto-scaling" ${"downscale-only"===n?"data-downscale-only":""}>${e}</marp-auto-scaling>`}this.shadowRoot.innerHTML=t+e}};let r;const a=Symbol();let l;const c="marpitSVGPolyfill:setZoomFactor,",d=Symbol(),g=Symbol();const h=()=>{const t="Apple Computer, Inc."===navigator.vendor,e=t?[u]:[],i={then:e=>(t?(async()=>{if(void 0===l){const t=document.createElement("canvas");t.width=10,t.height=10;const e=t.getContext("2d"),i=new Image(10,10),n=new Promise((t=>{i.addEventListener("load",(()=>t()))}));i.crossOrigin="anonymous",i.src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2210%22%20height%3D%2210%22%20viewBox%3D%220%200%201%201%22%3E%3CforeignObject%20width%3D%221%22%20height%3D%221%22%20requiredExtensions%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxhtml%22%3E%3Cdiv%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxhtml%22%20style%3D%22width%3A%201px%3B%20height%3A%201px%3B%20background%3A%20red%3B%20position%3A%20relative%22%3E%3C%2Fdiv%3E%3C%2FforeignObject%3E%3C%2Fsvg%3E",await n,e.drawImage(i,0,0),l=e.getImageData(5,5,1,1).data[3]<128}return l})().then((t=>{null==e||e(t?[u]:[])})):null==e||e([]),i)};return Object.assign(e,i)};let p,m;function u(t){const e="object"==typeof t&&t.target||document,i="object"==typeof t?t.zoom:t;window[g]||(Object.defineProperty(window,g,{configurable:!0,value:!0}),document.body.style.zoom=1.0001,document.body.offsetHeight,document.body.style.zoom=1,window.addEventListener("message",(({data:t,origin:e})=>{if(e===window.origin)try{if(t&&"string"==typeof t&&t.startsWith(c)){const[,e]=t.split(","),i=Number.parseFloat(e);Number.isNaN(i)||(m=i)}}catch(t){console.error(t)}})));let n=!1;Array.from(e.querySelectorAll("svg[data-marpit-svg]"),(t=>{var e,s,o,r;t.style.transform||(t.style.transform="translateZ(0)");const a=i||m||t.currentScale||1;p!==a&&(p=a,n=a);const l=t.getBoundingClientRect(),{length:c}=t.children;for(let i=0;i<c;i+=1){const n=t.children[i];if(n.getScreenCTM){const t=n.getScreenCTM();if(t){const i=null!==(s=null===(e=n.x)||void 0===e?void 0:e.baseVal.value)&&void 0!==s?s:0,c=null!==(r=null===(o=n.y)||void 0===o?void 0:o.baseVal.value)&&void 0!==r?r:0,d=n.children.length;for(let e=0;e<d;e+=1){const s=n.children[e];if("SECTION"===s.tagName){const{style:e}=s;e.transformOrigin||(e.transformOrigin=`${-i}px ${-c}px`),e.transform=`scale(${a}) matrix(${t.a}, ${t.b}, ${t.c}, ${t.d}, ${t.e-l.left}, ${t.f-l.top}) translateZ(0.0001px)`;break}}}}}})),!1!==n&&Array.from(e.querySelectorAll("iframe"),(({contentWindow:t})=>{null==t||t.postMessage(`${c}${n}`,"null"===window.origin?"*":window.origin)}))}function v({once:t=!1,target:e=document}={}){const i=function(t=document){if(t[d])return t[d];let e=!0;const i=()=>{e=!1,delete t[d]};Object.defineProperty(t,d,{configurable:!0,value:i});let n=[],s=!1;(async()=>{try{n=await h()}finally{s=!0}})();const o=()=>{for(const e of n)e({target:t});s&&0===n.length||e&&window.requestAnimationFrame(o)};return o(),i}(e);return t?(i(),()=>{}):i}p=1,m=void 0;const b=Symbol(),w=(e=document)=>{if("undefined"==typeof window)throw new Error("Marp Core's browser script is valid only in browser context.");if(((e=document)=>{const i=window[a];i||customElements.define("marp-auto-scaling",s);for(const n of Object.keys(t)){const s=`marp-${n}`,a=t[n].proto();null!=r||(r=!!document.createElement("div",{is:"marp-auto-scaling"}).outerHTML.startsWith("<div is")),r&&a!==HTMLElement?i||customElements.define(s,o(a,{style:t[n].style}),{extends:n}):(i||customElements.define(s,o(HTMLElement,t[n])),e.querySelectorAll(`${n}[is="${s}"]`).forEach((t=>{t.outerHTML=t.outerHTML.replace(new RegExp(`^<${n}`,"i"),`<${s}`).replace(new RegExp(`</${n}>$`,"i"),`</${s}>`)})))}window[a]=!0})(e),e[b])return e[b];const i=v({target:e}),n=()=>{i(),delete e[b]},l=Object.assign(n,{cleanup:n,update:()=>w(e)});return Object.defineProperty(e,b,{configurable:!0,value:l}),l},y=document.currentScript;w(y?y.getRootNode():document)}();
</script></foreignObject></svg></div><script>/*!! License: https://unpkg.com/@marp-team/marp-cli@2.5.0/lib/bespoke.js.LICENSE.txt */
!function(){"use strict";function e(e){return e&&e.__esModule&&Object.prototype.hasOwnProperty.call(e,"default")?e.default:e}var t={from:function(e,t){var n,r=1===(e.parent||e).nodeType?e.parent||e:document.querySelector(e.parent||e),o=[].filter.call("string"==typeof e.slides?r.querySelectorAll(e.slides):e.slides||r.children,(function(e){return"SCRIPT"!==e.nodeName})),i={},a=function(e,t){return(t=t||{}).index=o.indexOf(e),t.slide=e,t},s=function(e,t){i[e]=(i[e]||[]).filter((function(e){return e!==t}))},l=function(e,t){return(i[e]||[]).reduce((function(e,n){return e&&!1!==n(t)}),!0)},c=function(e,t){o[e]&&(n&&l("deactivate",a(n,t)),n=o[e],l("activate",a(n,t)))},d=function(e,t){var r=o.indexOf(n)+e;l(e>0?"next":"prev",a(n,t))&&c(r,t)},u={off:s,on:function(e,t){return(i[e]||(i[e]=[])).push(t),s.bind(null,e,t)},fire:l,slide:function(e,t){if(!arguments.length)return o.indexOf(n);l("slide",a(o[e],t))&&c(e,t)},next:d.bind(null,1),prev:d.bind(null,-1),parent:r,slides:o,destroy:function(e){l("destroy",a(n,e)),i={}}};return(t||[]).forEach((function(e){e(u)})),n||c(0),u}},n=e(t);const r=document.body,o=(...e)=>history.replaceState(...e),i="presenter",a="next",s=["",i,a],l="bespoke-marp-",c=`data-${l}`,d=(e,{protocol:t,host:n,pathname:r,hash:o}=location)=>{const i=e.toString();return`${t}//${n}${r}${i?"?":""}${i}${o}`},u=()=>r.dataset.bespokeView,f=e=>new URLSearchParams(location.search).get(e),m=(e,t={})=>{var n;const r={location,setter:o,...t},i=new URLSearchParams(r.location.search);for(const t of Object.keys(e)){const n=e[t];"string"==typeof n?i.set(t,n):i.delete(t)}try{r.setter({...null!==(n=window.history.state)&&void 0!==n?n:{}},"",d(i,r.location))}catch(e){console.error(e)}},g=(()=>{const e="bespoke-marp";try{return localStorage.setItem(e,e),localStorage.removeItem(e),!0}catch(e){return!1}})(),p=e=>{try{return localStorage.getItem(e)}catch(e){return null}},v=(e,t)=>{try{return localStorage.setItem(e,t),!0}catch(e){return!1}},h=e=>{try{return localStorage.removeItem(e),!0}catch(e){return!1}},y=(e,t)=>{const n="aria-hidden";t?e.setAttribute(n,"true"):e.removeAttribute(n)},b=e=>{e.parent.classList.add(`${l}parent`),e.slides.forEach((e=>e.classList.add(`${l}slide`))),e.on("activate",(t=>{const n=`${l}active`,r=t.slide,o=r.classList,i=!o.contains(n);if(e.slides.forEach((e=>{e.classList.remove(n),y(e,!0)})),o.add(n),y(r,!1),i){const e=`${n}-ready`;o.add(e),document.body.clientHeight,o.remove(e)}}))},w=e=>{let t=0,n=0;Object.defineProperty(e,"fragments",{enumerable:!0,value:e.slides.map((e=>[null,...e.querySelectorAll("[data-marpit-fragment]")]))});const r=r=>void 0!==e.fragments[t][n+r],o=(r,o)=>{t=r,n=o,e.fragments.forEach(((e,t)=>{e.forEach(((e,n)=>{if(null==e)return;const i=t<r||t===r&&n<=o;e.setAttribute(`${c}fragment`,(i?"":"in")+"active");const a=`${c}current-fragment`;t===r&&n===o?e.setAttribute(a,"current"):e.removeAttribute(a)}))})),e.fragmentIndex=o;const i={slide:e.slides[r],index:r,fragments:e.fragments[r],fragmentIndex:o};e.fire("fragment",i)};e.on("next",(({fragment:i=!0})=>{if(i){if(r(1))return o(t,n+1),!1;const i=t+1;e.fragments[i]&&o(i,0)}else{const r=e.fragments[t].length;if(n+1<r)return o(t,r-1),!1;const i=e.fragments[t+1];i&&o(t+1,i.length-1)}})),e.on("prev",(({fragment:i=!0})=>{if(r(-1)&&i)return o(t,n-1),!1;const a=t-1;e.fragments[a]&&o(a,e.fragments[a].length-1)})),e.on("slide",(({index:t,fragment:n})=>{let r=0;if(void 0!==n){const o=e.fragments[t];if(o){const{length:e}=o;r=-1===n?e-1:Math.min(Math.max(n,0),e-1)}}o(t,r)})),o(0,0)},x=document,k=()=>!(!x.fullscreenEnabled&&!x.webkitFullscreenEnabled),$=()=>!(!x.fullscreenElement&&!x.webkitFullscreenElement),E=e=>{e.fullscreen=()=>{k()&&(async()=>{return $()?null===(e=x.exitFullscreen||x.webkitExitFullscreen)||void 0===e?void 0:e.call(x):((e=x.body)=>{var t;return null===(t=e.requestFullscreen||e.webkitRequestFullscreen)||void 0===t?void 0:t.call(e)})();var e})()},document.addEventListener("keydown",(t=>{"f"!==t.key&&"F11"!==t.key||t.altKey||t.ctrlKey||t.metaKey||!k()||(e.fullscreen(),t.preventDefault())}))},L=`${l}inactive`,S=(e=2e3)=>({parent:t,fire:n})=>{const r=t.classList,o=e=>n(`marp-${e?"":"in"}active`);let i;const a=()=>{i&&clearTimeout(i),i=setTimeout((()=>{r.add(L),o()}),e),r.contains(L)&&(r.remove(L),o(!0))};for(const e of["mousedown","mousemove","touchend"])document.addEventListener(e,a);setTimeout(a,0)},P=["AUDIO","BUTTON","INPUT","SELECT","TEXTAREA","VIDEO"],_=e=>{e.parent.addEventListener("keydown",(e=>{if(!e.target)return;const t=e.target;(P.includes(t.nodeName)||"true"===t.contentEditable)&&e.stopPropagation()}))},T=e=>{window.addEventListener("load",(()=>{for(const t of e.slides){const e=t.querySelector("marp-auto-scaling, [data-auto-scaling], [data-marp-fitting]");t.setAttribute(`${c}load`,e?"":"hideable")}}))},I=({interval:e=250}={})=>t=>{document.addEventListener("keydown",(e=>{if(" "===e.key&&e.shiftKey)t.prev();else if("ArrowLeft"===e.key||"ArrowUp"===e.key||"PageUp"===e.key)t.prev({fragment:!e.shiftKey});else if(" "!==e.key||e.shiftKey)if("ArrowRight"===e.key||"ArrowDown"===e.key||"PageDown"===e.key)t.next({fragment:!e.shiftKey});else if("End"===e.key)t.slide(t.slides.length-1,{fragment:-1});else{if("Home"!==e.key)return;t.slide(0)}else t.next();e.preventDefault()}));let n,r,o=0;t.parent.addEventListener("wheel",(i=>{let a=!1;const s=(e,t)=>{e&&(a=a||((e,t)=>((e,t)=>{const n="X"===t?"Width":"Height";return e[`client${n}`]<e[`scroll${n}`]})(e,t)&&((e,t)=>{const{overflow:n}=e,r=e[`overflow${t}`];return"auto"===n||"scroll"===n||"auto"===r||"scroll"===r})(getComputedStyle(e),t))(e,t)),(null==e?void 0:e.parentElement)&&s(e.parentElement,t)};if(0!==i.deltaX&&s(i.target,"X"),0!==i.deltaY&&s(i.target,"Y"),a)return;i.preventDefault();const l=Math.sqrt(i.deltaX**2+i.deltaY**2);if(void 0!==i.wheelDelta){if(void 0===i.webkitForce&&Math.abs(i.wheelDelta)<40)return;if(i.deltaMode===i.DOM_DELTA_PIXEL&&l<4)return}else if(i.deltaMode===i.DOM_DELTA_PIXEL&&l<12)return;r&&clearTimeout(r),r=setTimeout((()=>{n=0}),e);const c=Date.now()-o<e,d=l<=n;if(n=l,c||d)return;let u;(i.deltaX>0||i.deltaY>0)&&(u="next"),(i.deltaX<0||i.deltaY<0)&&(u="prev"),u&&(t[u](),o=Date.now())}))},M=(e=`.${l}osc`)=>{const t=document.querySelector(e);if(!t)return()=>{};const n=(e,n)=>{t.querySelectorAll(`[${c}osc=${JSON.stringify(e)}]`).forEach(n)};return k()||n("fullscreen",(e=>e.style.display="none")),g||n("presenter",(e=>{e.disabled=!0,e.title="Presenter view is disabled due to restricted localStorage."})),e=>{t.addEventListener("click",(t=>{if(t.target instanceof HTMLElement){const{bespokeMarpOsc:n}=t.target.dataset;n&&t.target.blur();const r={fragment:!t.shiftKey};"next"===n?e.next(r):"prev"===n?e.prev(r):"fullscreen"===n?null==e||e.fullscreen():"presenter"===n&&e.openPresenterView()}})),e.parent.appendChild(t),e.on("activate",(({index:t})=>{n("page",(n=>n.textContent=`Page ${t+1} of ${e.slides.length}`))})),e.on("fragment",(({index:t,fragments:r,fragmentIndex:o})=>{n("prev",(e=>e.disabled=0===t&&0===o)),n("next",(n=>n.disabled=t===e.slides.length-1&&o===r.length-1))})),e.on("marp-active",(()=>y(t,!1))),e.on("marp-inactive",(()=>y(t,!0))),k()&&(e=>{for(const t of["","webkit"])x.addEventListener(t+"fullscreenchange",e)})((()=>n("fullscreen",(e=>e.classList.toggle("exit",k()&&$())))))}},O=e=>{window.addEventListener("message",(t=>{if(t.origin!==window.origin)return;const[n,r]=t.data.split(":");if("navigate"===n){const[t,n]=r.split(",");let o=Number.parseInt(t,10),i=Number.parseInt(n,10)+1;i>=e.fragments[o].length&&(o+=1,i=0),e.slide(o,{fragment:i})}}))};var A=["area","base","br","col","command","embed","hr","img","input","keygen","link","meta","param","source","track","wbr"];let C=e=>String(e).replace(/[&<>"']/g,(e=>`&${D[e]};`)),D={"&":"amp","<":"lt",">":"gt",'"':"quot","'":"apos"},N="dangerouslySetInnerHTML",B={className:"class",htmlFor:"for"},q={};function K(e,t){let n=[],r="";t=t||{};for(let e=arguments.length;e-- >2;)n.push(arguments[e]);if("function"==typeof e)return t.children=n.reverse(),e(t);if(e){if(r+="<"+e,t)for(let e in t)!1!==t[e]&&null!=t[e]&&e!==N&&(r+=` ${B[e]?B[e]:C(e)}="${C(t[e])}"`);r+=">"}if(-1===A.indexOf(e)){if(t[N])r+=t[N].__html;else for(;n.length;){let e=n.pop();if(e)if(e.pop)for(let t=e.length;t--;)n.push(e[t]);else r+=!0===q[e]?e:C(e)}r+=e?`</${e}>`:""}return q[r]=!0,r}const j=({children:e})=>K(null,null,...e),F=`${l}presenter-`,V={container:`${F}container`,dragbar:`${F}dragbar-container`,next:`${F}next`,nextContainer:`${F}next-container`,noteContainer:`${F}note-container`,noteWrapper:`${F}note-wrapper`,noteButtons:`${F}note-buttons`,infoContainer:`${F}info-container`,infoPage:`${F}info-page`,infoPageText:`${F}info-page-text`,infoPagePrev:`${F}info-page-prev`,infoPageNext:`${F}info-page-next`,noteButtonsBigger:`${F}note-bigger`,noteButtonsSmaller:`${F}note-smaller`,infoTime:`${F}info-time`,infoTimer:`${F}info-timer`},U=e=>{const{title:t}=document;document.title="[Presenter view]"+(t?` - ${t}`:"");const n={},r=e=>(n[e]=n[e]||document.querySelector(`.${e}`),n[e]);document.body.appendChild((e=>{const t=document.createElement("div");return t.className=V.container,t.appendChild(e),t.insertAdjacentHTML("beforeend",K(j,null,K("div",{class:V.nextContainer},K("iframe",{class:V.next,src:"?view=next"})),K("div",{class:V.dragbar}),K("div",{class:V.noteContainer},K("div",{class:V.noteWrapper}),K("div",{class:V.noteButtons},K("button",{class:V.noteButtonsSmaller,tabindex:"-1",title:"Smaller notes font size"},"Smaller notes font size"),K("button",{class:V.noteButtonsBigger,tabindex:"-1",title:"Bigger notes font size"},"Bigger notes font size"))),K("div",{class:V.infoContainer},K("div",{class:V.infoPage},K("button",{class:V.infoPagePrev,tabindex:"-1",title:"Previous"},"Previous"),K("span",{class:V.infoPageText}),K("button",{class:V.infoPageNext,tabindex:"-1",title:"Next"},"Next")),K("time",{class:V.infoTime,title:"Current time"}),K("time",{class:V.infoTimer,title:"Timer"})))),t})(e.parent)),(e=>{let t=!1;r(V.dragbar).addEventListener("mousedown",(()=>{t=!0,r(V.dragbar).classList.add("active")})),window.addEventListener("mouseup",(()=>{t=!1,r(V.dragbar).classList.remove("active")})),window.addEventListener("mousemove",(e=>{if(!t)return;const n=e.clientX/document.documentElement.clientWidth*100;r(V.container).style.setProperty("--bespoke-marp-presenter-split-ratio",`${Math.max(0,Math.min(100,n))}%`)})),r(V.nextContainer).addEventListener("click",(()=>e.next()));const n=r(V.next),o=(i=n,(e,t)=>{var n;return null===(n=i.contentWindow)||void 0===n?void 0:n.postMessage(`navigate:${e},${t}`,"null"===window.origin?"*":window.origin)});var i;n.addEventListener("load",(()=>{r(V.nextContainer).classList.add("active"),o(e.slide(),e.fragmentIndex),e.on("fragment",(({index:e,fragmentIndex:t})=>o(e,t)))}));const a=document.querySelectorAll(".bespoke-marp-note");a.forEach((e=>{e.addEventListener("keydown",(e=>e.stopPropagation())),r(V.noteWrapper).appendChild(e)})),e.on("activate",(()=>a.forEach((t=>t.classList.toggle("active",t.dataset.index==e.slide())))));let s=0;const l=e=>{s=Math.max(-5,s+e),r(V.noteContainer).style.setProperty("--bespoke-marp-note-font-scale",(1.2**s).toFixed(4))},c=()=>l(1),d=()=>l(-1),u=r(V.noteButtonsBigger),f=r(V.noteButtonsSmaller);u.addEventListener("click",(()=>{u.blur(),c()})),f.addEventListener("click",(()=>{f.blur(),d()})),document.addEventListener("keydown",(e=>{"+"===e.key&&c(),"-"===e.key&&d()}),!0),e.on("activate",(({index:t})=>{r(V.infoPageText).textContent=`${t+1} / ${e.slides.length}`}));const m=r(V.infoPagePrev),g=r(V.infoPageNext);m.addEventListener("click",(t=>{m.blur(),e.prev({fragment:!t.shiftKey})})),g.addEventListener("click",(t=>{g.blur(),e.next({fragment:!t.shiftKey})})),e.on("fragment",(({index:t,fragments:n,fragmentIndex:r})=>{m.disabled=0===t&&0===r,g.disabled=t===e.slides.length-1&&r===n.length-1}));let p=new Date;const v=()=>{const e=new Date,t=e=>`${Math.floor(e)}`.padStart(2,"0"),n=e.getTime()-p.getTime(),o=t(n/1e3%60),i=t(n/1e3/60%60),a=t(n/36e5%24);r(V.infoTime).textContent=e.toLocaleTimeString(),r(V.infoTimer).textContent=`${a}:${i}:${o}`};v(),setInterval(v,250),r(V.infoTimer).addEventListener("click",(()=>{p=new Date}))})(e)},X=e=>{if(!(e=>e.syncKey&&"string"==typeof e.syncKey)(e))throw new Error("The current instance of Bespoke.js is invalid for Marp bespoke presenter plugin.");Object.defineProperties(e,{openPresenterView:{enumerable:!0,value:H},presenterUrl:{enumerable:!0,get:R}}),g&&document.addEventListener("keydown",(t=>{"p"!==t.key||t.altKey||t.ctrlKey||t.metaKey||(t.preventDefault(),e.openPresenterView())}))};function H(){const{max:e,floor:t}=Math,n=e(t(.85*window.innerWidth),640),r=e(t(.85*window.innerHeight),360);return window.open(this.presenterUrl,F+this.syncKey,`width=${n},height=${r},menubar=no,toolbar=no`)}function R(){const e=new URLSearchParams(location.search);return e.set("view","presenter"),e.set("sync",this.syncKey),d(e)}const W=e=>{const t=u();return t===a&&e.appendChild(document.createElement("span")),{"":X,[i]:U,[a]:O}[t]},J=e=>{e.on("activate",(t=>{document.querySelectorAll(".bespoke-progress-parent > .bespoke-progress-bar").forEach((n=>{n.style.flexBasis=100*t.index/(e.slides.length-1)+"%"}))}))},Y=e=>{const t=Number.parseInt(e,10);return Number.isNaN(t)?null:t},z=(e={})=>{const t={history:!0,...e};return e=>{let n=!0;const r=e=>{const t=n;try{return n=!0,e()}finally{n=t}},o=(t={fragment:!0})=>{let n=t.fragment?Y(f("f")||""):null;((t,n)=>{const{min:r,max:o}=Math,{fragments:i,slides:a}=e,s=o(0,r(t,a.length-1)),l=o(0,r(n||0,i[s].length-1));s===e.slide()&&l===e.fragmentIndex||e.slide(s,{fragment:l})})((()=>{var t,r;if(location.hash){const[o]=location.hash.slice(1).split(":~:");if(/^\d+$/.test(o))return(null!==(t=Y(o))&&void 0!==t?t:1)-1;const i=document.getElementById(o)||document.querySelector(`a[name="${CSS.escape(o)}"]`);if(i){const{length:t}=e.slides;for(let o=0;o<t;o+=1)if(e.slides[o].contains(i)){const t=null===(r=e.fragments)||void 0===r?void 0:r[o],a=i.closest("[data-marpit-fragment]");if(t&&a){const e=t.indexOf(a);e>=0&&(n=e)}return o}}}return 0})(),n)};e.on("fragment",(({index:e,fragmentIndex:r})=>{n||m({f:0===r||r.toString()},{location:{...location,hash:`#${e+1}`},setter:(...e)=>t.history?history.pushState(...e):history.replaceState(...e)})})),setTimeout((()=>{o(),window.addEventListener("hashchange",(()=>r((()=>{o({fragment:!1}),m({f:void 0})})))),window.addEventListener("popstate",(()=>{n||r((()=>o()))})),n=!1}),0)}},G=(e={})=>{var t;const n=e.key||(null===(t=window.history.state)||void 0===t?void 0:t.marpBespokeSyncKey)||Math.random().toString(36).slice(2),r=`bespoke-marp-sync-${n}`;var i;i={marpBespokeSyncKey:n},m({},{setter:(e,...t)=>o({...e,...i},...t)});const a=()=>{const e=p(r);return e?JSON.parse(e):Object.create(null)},s=e=>{const t=a(),n={...t,...e(t)};return v(r,JSON.stringify(n)),n},l=()=>{window.removeEventListener("pageshow",l),s((e=>({reference:(e.reference||0)+1})))};return e=>{l(),Object.defineProperty(e,"syncKey",{value:n,enumerable:!0});let t=!0;setTimeout((()=>{e.on("fragment",(e=>{t&&s((()=>({index:e.index,fragmentIndex:e.fragmentIndex})))}))}),0),window.addEventListener("storage",(n=>{if(n.key===r&&n.oldValue&&n.newValue){const r=JSON.parse(n.oldValue),o=JSON.parse(n.newValue);if(r.index!==o.index||r.fragmentIndex!==o.fragmentIndex)try{t=!1,e.slide(o.index,{fragment:o.fragmentIndex,forSync:!0})}finally{t=!0}}}));const o=()=>{const{reference:e}=a();void 0===e||e<=1?h(r):s((()=>({reference:e-1})))};window.addEventListener("pagehide",(e=>{e.persisted&&window.addEventListener("pageshow",l),o()})),e.on("destroy",o)}},{PI:Q,abs:Z,sqrt:ee,atan2:te}=Math,ne={passive:!0},re=({slope:e=-.7,swipeThreshold:t=30}={})=>n=>{let r;const o=n.parent,i=e=>{const t=o.getBoundingClientRect();return{x:e.pageX-(t.left+t.right)/2,y:e.pageY-(t.top+t.bottom)/2}};o.addEventListener("touchstart",(({touches:e})=>{r=1===e.length?i(e[0]):void 0}),ne),o.addEventListener("touchmove",(e=>{if(r)if(1===e.touches.length){e.preventDefault();const t=i(e.touches[0]),n=t.x-r.x,o=t.y-r.y;r.delta=ee(Z(n)**2+Z(o)**2),r.radian=te(n,o)}else r=void 0})),o.addEventListener("touchend",(o=>{if(r){if(r.delta&&r.delta>=t&&r.radian){const t=(r.radian-e+Q)%(2*Q)-Q;n[t<0?"next":"prev"](),o.stopPropagation()}r=void 0}}),ne)},oe=new Map;oe.clear(),oe.set("none",{backward:{both:void 0,incoming:void 0,outgoing:void 0},forward:{both:void 0,incoming:void 0,outgoing:void 0}});const ie={both:"",outgoing:"outgoing-",incoming:"incoming-"},ae={forward:"",backward:"-backward"},se=e=>`--marp-bespoke-transition-animation-${e}`,le=e=>`--marp-transition-${e}`,ce=se("name"),de=se("duration"),ue=e=>new Promise((t=>{const n={},r=document.createElement("div"),o=e=>{r.remove(),t(e)};r.addEventListener("animationstart",(()=>o(n))),Object.assign(r.style,{animationName:e,animationDuration:"1s",animationFillMode:"both",animationPlayState:"paused",position:"absolute",pointerEvents:"none"}),document.body.appendChild(r);const i=getComputedStyle(r).getPropertyValue(le("duration"));i&&(n.defaultDuration=i),((e,t)=>{requestAnimationFrame((()=>{e.style.animationPlayState="running",requestAnimationFrame((()=>t(void 0)))}))})(r,o)})),fe=async e=>oe.has(e)?oe.get(e):(e=>{const t={},n=[];for(const[r,o]of Object.entries(ie))for(const[i,a]of Object.entries(ae)){const s=`marp-${o}transition${a}-${e}`;n.push(ue(s).then((e=>{t[i]=t[i]||{},t[i][r]=e?{...e,name:s}:void 0})))}return Promise.all(n).then((()=>t))})(e).then((t=>(oe.set(e,t),t))),me=e=>Object.values(e).flatMap(Object.values).every((e=>!e)),ge=(e,{type:t,backward:n})=>{const r=e[n?"backward":"forward"],o=(()=>{const e=r[t],n=e=>({[ce]:e.name});if(e)return n(e);if(r.both){const e=n(r.both);return"incoming"===t&&(e[se("direction")]="reverse"),e}})();return!o&&n?ge(e,{type:t,backward:!1}):o||{[ce]:"__bespoke_marp_transition_no_animation__"}},pe=e=>{if(e)try{const t=JSON.parse(e);if((e=>{if("object"!=typeof e)return!1;const t=e;return"string"==typeof t.name&&(void 0===t.duration||"string"==typeof t.duration)})(t))return t}catch(e){}},ve="_tSId",he="_tA",ye="bespoke-marp-transition-warming-up",be=window.matchMedia("(prefers-reduced-motion: reduce)"),we="__bespoke_marp_transition_reduced_outgoing__",xe="__bespoke_marp_transition_reduced_incoming__",ke={forward:{both:void 0,incoming:{name:xe},outgoing:{name:we}},backward:{both:void 0,incoming:{name:xe},outgoing:{name:we}}},$e=e=>{if(!document.startViewTransition)return;const t=t=>(void 0!==t&&(e._tD=t),e._tD);let n;t(!1),((...e)=>{const t=[...new Set(e).values()];return Promise.all(t.map((e=>fe(e)))).then()})(...Array.from(document.querySelectorAll("section[data-transition], section[data-transition-back]")).flatMap((e=>[e.dataset.transition,e.dataset.transitionBack].flatMap((e=>{const t=pe(e);return[null==t?void 0:t.name,(null==t?void 0:t.builtinFallback)?`__builtin__${t.name}`:void 0]})).filter((e=>!!e))))).then((()=>{document.querySelectorAll("style").forEach((e=>{e.innerHTML=e.innerHTML.replace(/--marp-transition-duration:[^;}]*[;}]/g,(e=>e.slice(0,-1)+"!important"+e.slice(-1)))}))}));const r=(n,{back:r,cond:o})=>i=>{var a;const s=t();if(s)return!!i[he]||!("object"!=typeof s||(s.skipTransition(),!i.forSync));if(!o(i))return!0;const l=e.slides[e.slide()],c=()=>{var e;return null!==(e=i.back)&&void 0!==e?e:r},d="data-transition"+(c()?"-back":""),u=l.querySelector(`section[${d}]`);if(!u)return!0;const f=pe(null!==(a=u.getAttribute(d))&&void 0!==a?a:void 0);return!f||((async(e,{builtinFallback:t=!0}={})=>{let n=await fe(e);if(me(n)){if(!t)return;return n=await fe(`__builtin__${e}`),me(n)?void 0:n}return n})(f.name,{builtinFallback:f.builtinFallback}).then((e=>{if(!e){t(!0);try{n(i)}finally{t(!1)}return}let r=e;be.matches&&(console.warn("Use a constant animation to transition because preferring reduced motion by viewer has detected."),r=ke);const o=document.getElementById(ve);o&&o.remove();const a=document.createElement("style");a.id=ve,document.head.appendChild(a),((e,t)=>{const n=[`:root{${le("direction")}:${t.backward?-1:1};}`,":root:has(.bespoke-marp-inactive){cursor:none;}"],r=t=>{var n,o,i;const a=(null===(n=e[t].both)||void 0===n?void 0:n.defaultDuration)||(null===(o=e[t].outgoing)||void 0===o?void 0:o.defaultDuration)||(null===(i=e[t].incoming)||void 0===i?void 0:i.defaultDuration);return"forward"===t?a:a||r("forward")},o=t.duration||r(t.backward?"backward":"forward");void 0!==o&&n.push(`::view-transition-group(*){${de}:${o};}`);const i=e=>Object.entries(e).map((([e,t])=>`${e}:${t};`)).join("");return n.push(`::view-transition-old(root){${i(ge(e,{...t,type:"outgoing"}))}}`,`::view-transition-new(root){${i(ge(e,{...t,type:"incoming"}))}}`),n})(r,{backward:c(),duration:f.duration}).forEach((e=>{var t;return null===(t=a.sheet)||void 0===t?void 0:t.insertRule(e)}));const s=document.documentElement.classList;s.add(ye);let l=!1;const d=()=>{l||(n(i),l=!0,s.remove(ye))},u=()=>{t(!1),a.remove(),s.remove(ye)};try{t(!0);const e=document.startViewTransition(d);t(e),e.finished.finally(u)}catch(e){console.error(e),d(),u()}})),!1)};e.on("prev",r((t=>e.prev({...t,[he]:!0})),{back:!0,cond:e=>{var t;return e.index>0&&!((null===(t=e.fragment)||void 0===t||t)&&n.fragmentIndex>0)}})),e.on("next",r((t=>e.next({...t,[he]:!0})),{cond:t=>t.index+1<e.slides.length&&!(n.fragmentIndex+1<n.fragments.length)})),setTimeout((()=>{e.on("slide",r((t=>e.slide(t.index,{...t,[he]:!0})),{cond:t=>{const n=e.slide();return t.index!==n&&(t.back=t.index<n,!0)}}))}),0),e.on("fragment",(e=>{n=e}))};let Ee;const Le=()=>(void 0===Ee&&(Ee="wakeLock"in navigator&&navigator.wakeLock),Ee),Se=async()=>{const e=Le();if(e)try{return await e.request("screen")}catch(e){console.warn(e)}return null},Pe=async()=>{if(!Le())return;let e;const t=()=>{e&&"visible"===document.visibilityState&&Se()};for(const e of["visibilitychange","fullscreenchange"])document.addEventListener(e,t);return e=await Se(),e};((e=document.getElementById(":$p"))=>{(()=>{const e=f("view");r.dataset.bespokeView=e===a||e===i?e:""})();const t=(e=>{const t=f(e);return m({[e]:void 0}),t})("sync")||void 0;n.from(e,((...e)=>{const t=s.findIndex((e=>u()===e));return e.map((([e,n])=>e[t]&&n)).filter((e=>e))})([[1,1,0],G({key:t})],[[1,1,1],W(e)],[[1,1,0],_],[[1,1,1],b],[[1,0,0],S()],[[1,1,1],T],[[1,1,1],z({history:!1})],[[1,1,0],I()],[[1,1,0],E],[[1,0,0],J],[[1,1,0],re()],[[1,0,0],M()],[[1,0,0],$e],[[1,1,1],w],[[1,1,0],Pe]))})()}();</script></body></html>