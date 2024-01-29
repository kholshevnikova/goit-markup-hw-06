.header-nav-item {
color: var(--NAVY-BLUE, #2e2f42);
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
padding-top: 24px;
display: block;
padding-bottom: 24px;
position: relative;
transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.header-nav-item:hover {
color: #404bbf;
}

.header-nav-item:focus {
color: #404bbf;
}
.active:active {
color: #404bbf;
}
.active:active::after {
content: "";
border-radius: 2px;
background: #404bbf;
width: 48px;
height: 4px;
position: absolute;
left: 0;
bottom: -1px;}
