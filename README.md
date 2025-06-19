# goit-markup-hw-01

footer

.page-footer {
background-color: #2e2f42;
padding-top: 96px;
padding-bottom: 96px;
}

.footer-container {
display: flex;
flex-direction: column;
align-items: center;
max-width: 320px;
margin: 0 auto;
padding: 0 16px;
gap: 72px;
}

.logo-goal {
text-align: center;
margin-bottom: 0;
}

.footer-logo {
display: inline-block;
margin-bottom: 16px;
text-align: center;
}

.footer-text {
font-weight: 400;
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
width: 264px;
margin: 0 auto;
text-align: center;
}

.footer-media {
margin: 0 auto;
}

.social-media {
font-weight: 500;
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
color: #ffffff;
margin-bottom: 16px;
text-align: center;
}

.media-list {
display: flex;
justify-content: center;
gap: 16px;
padding: 0;
margin: 0;
list-style: none;
}

.footer-icon-social {
fill: #f4f4fd;
}

.footer-social-link {
display: flex;
justify-content: center;
align-items: center;
width: 40px;
height: 40px;
border-radius: 50%;
background-color: #4d5ae5;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.footer-social-link:hover,
.footer-social-link:focus {
background-color: #31d0aa;
}

.subscribe-part {
display: flex;
flex-direction: column;
align-items: center;
text-align: center;
padding: 16px 0;
}

.footer-form {
display: flex;
flex-direction: column;
align-items: center;
gap: 16px;
}

.subscribe-title {
font-weight: 500;
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
color: #ffffff;
margin-bottom: 16px;
display: block;
text-align: center;
}

.footer-subscribe {
width: 100%;
max-width: 264px;
}

.footer-input {
border: 1px solid #fff;
border-radius: 4px;
width: 264px;
height: 40px;
background-color: transparent;
padding-left: 16px;
padding-right: 16px;
color: #fff;
font-weight: 400;
font-size: 12px;
line-height: 2;
letter-spacing: 0.04em;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);

}

.footer-input:focus,
.footer-input:hover {
border: 1px solid #4d5ae5;
outline: none;
}
.footer-input::placeholder {
font-size: 12px;
line-height: 2;
letter-spacing: 0.04em;
}

.footer-btn {
font-weight: 500;
border: none;
background-color: #4d5ae5;
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.04em;
text-align: center;
color: #fff;
border-radius: 4px;
height: 40px;
cursor: pointer;
display: flex;
align-items: center;
justify-content: center;
gap: 16px;
padding: 8px 24px;

box-shadow: 0 4px 4px 0 rgba(0, 0, 0, 0.15);
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
position: relative;
margin: 0 auto;
}

.footer-btn:hover,
.footer-btn:focus {
background-color: #404bbf;
}

.footer-send-icon {
transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
fill: #fff;
position: static;
margin-left: 0;
}
