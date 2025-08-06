# CSS de Changa

:root {

&nbsp; --blue: #0B1D33;

&nbsp; --orange: #FF6F00;

&nbsp; --white: #FFFFFF;

&nbsp; --grey: #F5F7FA;

&nbsp; --radius: 8px;

&nbsp; --shadow: 0 4px 12px rgba(0,0,0,.1);

}



\* {

&nbsp; margin: 0;

&nbsp; padding: 0;

&nbsp; box-sizing: border-box;

}



body {

&nbsp; font-family: 'Inter', sans-serif;

&nbsp; color: var(--blue);

&nbsp; line-height: 1.6;

}



img {

&nbsp; width: 100%;

&nbsp; height: auto;

&nbsp; display: block;

&nbsp; border-radius: var(--radius);

}



.container {

&nbsp; width: 90%;

&nbsp; max-width: 1100px;

&nbsp; margin: 0 auto;

}



.grid-2 {

&nbsp; display: grid;

&nbsp; gap: 2rem;

&nbsp; align-items: center;

}



@media (min-width: 768px) {

&nbsp; .grid-2 {

&nbsp;   grid-template-columns: 1fr 1fr;

&nbsp; }

&nbsp; .order-2 { order: 2; }

}



/\* NAV \*/

.nav {

&nbsp; display: flex;

&nbsp; justify-content: space-between;

&nbsp; align-items: center;

&nbsp; padding: 1rem 0;

}

.logo { font-size: 1.8rem; font-weight: 700; color: var(--white); }

.nav\_\_links { list-style: none; display: flex; gap: 1.5rem; }

.nav\_\_links a { color: var(--white); text-decoration: none; font-weight: 600; }



/\* HERO \*/

.hero {

&nbsp; background: var(--blue);

&nbsp; color: var(--white);

&nbsp; min-height: 90vh;

&nbsp; display: flex;

&nbsp; flex-direction: column;

&nbsp; justify-content: space-between;

}

.hero\_\_content {

&nbsp; flex-grow: 1;

&nbsp; display: flex;

&nbsp; flex-direction: column;

&nbsp; justify-content: center;

&nbsp; text-align: center;

}

.hero\_\_content h2 {

&nbsp; font-size: 2.5rem;

&nbsp; margin-bottom: 1rem;

}

.hero\_\_content p {

&nbsp; max-width: 600px;

&nbsp; margin: 0 auto 2rem;

&nbsp; opacity: .9;

}



/\* BUTTONS \*/

.btn {

&nbsp; display: inline-block;

&nbsp; padding: .9rem 2rem;

&nbsp; border-radius: var(--radius);

&nbsp; font-weight: 600;

&nbsp; text-decoration: none;

&nbsp; cursor: pointer;

&nbsp; transition: .3s;

}

.btn--primary {

&nbsp; background: var(--orange);

&nbsp; color: var(--white);

}

.btn--outline {

&nbsp; border: 2px solid var(--orange);

&nbsp; color: var(--orange);

}

.btn--wa {

&nbsp; background: #25D366;

&nbsp; color: var(--white);

}

.btn:hover { transform: translateY(-2px); }



/\* SECTIONS \*/

.section {

&nbsp; padding: 4rem 0;

}

.bg-grey { background: var(--grey); }



/\* FORMS \*/

.form {

&nbsp; display: flex;

&nbsp; flex-direction: column;

&nbsp; gap: 1rem;

}

.form input,

.form select,

.form textarea {

&nbsp; padding: .75rem;

&nbsp; border: 1px solid #ccc;

&nbsp; border-radius: var(--radius);

&nbsp; font-size: 1rem;

}

.form button { align-self: flex-start; }



/\* PLANS \*/

.plans {

&nbsp; display: grid;

&nbsp; gap: 2rem;

&nbsp; margin-top: 2rem;

}

@media (min-width: 768px) {

&nbsp; .plans { grid-template-columns: repeat(3, 1fr); }

}

.plan {

&nbsp; background: var(--white);

&nbsp; border-radius: var(--radius);

&nbsp; padding: 2rem;

&nbsp; box-shadow: var(--shadow);

&nbsp; text-align: center;

}

.plan--featured {

&nbsp; border: 3px solid var(--orange);

&nbsp; transform: scale(1.05);

}

.price {

&nbsp; display: block;

&nbsp; font-size: 2rem;

&nbsp; font-weight: 700;

&nbsp; color: var(--orange);

}

.price span {

&nbsp; font-size: 1rem;

&nbsp; color: #666;

}

.plan ul {

&nbsp; list-style: none;

&nbsp; margin: 1.5rem 0;

&nbsp; text-align: left;

}

.plan li::before {

&nbsp; content: "✔";

&nbsp; color: var(--orange);

&nbsp; margin-right: .5rem;

}



/\* TESTIMONIALS \*/

.testimonials {

&nbsp; display: grid;

&nbsp; gap: 2rem;

}

@media (min-width: 768px) {

&nbsp; .testimonials { grid-template-columns: repeat(3, 1fr); }

}

blockquote {

&nbsp; background: var(--white);

&nbsp; padding: 1.5rem;

&nbsp; border-radius: var(--radius);

&nbsp; box-shadow: var(--shadow);

&nbsp; font-style: italic;

}

cite {

&nbsp; display: block;

&nbsp; margin-top: 1rem;

&nbsp; font-weight: 600;

&nbsp; color: var(--orange);

}



/\* FOOTER \*/

.footer {

&nbsp; text-align: center;

&nbsp; padding: 2rem 0;

&nbsp; font-size: .9rem;

&nbsp; color: #666;

}

