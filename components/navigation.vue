<template>
<div class="nav">
    <div class="logo">
        <h1> Shofy.</h1>
    </div>
    <div class="center-nav">
        <NuxtLink to="/">Home</NuxtLink>
        <div class="shop">
            <NuxtLink to="/shop">Shop</NuxtLink>
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24">
                <path fill="white" d="M12 14.708L6.692 9.4l.708-.708l4.6 4.6l4.6-4.6l.708.708z" />
            </svg>
        </div>
        <div class="pagess">
            <NuxtLink to="/page">Pages
            </NuxtLink>
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24">
                <path fill="white" d="M12 14.708L6.692 9.4l.708-.708l4.6 4.6l4.6-4.6l.708.708z" />
            </svg>
        </div>
    
    <NuxtLink to="/coupons">Coupons</NuxtLink>

    <div class="blogs">
        <NuxtLink to="/blog">Blog</NuxtLink>
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24">
                <path fill="white" d="M12 14.708L6.692 9.4l.708-.708l4.6 4.6l4.6-4.6l.708.708z" />
            </svg>
    </div>
    
    <NuxtLink to="/contact">Contact</NuxtLink>
</div>
<div class="end-nav">
    <div class="endlogo">
        <div class="endlogologo"><svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24">
                <path fill="white"
                    d="M12 11.385q-1.237 0-2.119-.882T9 8.385q0-1.238.881-2.12q.881-.88 2.119-.88t2.119.88q.881.882.881 2.12q0 1.237-.881 2.118T12 11.385m-7 7.23V16.97q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.833-1.018q1.418-.34 2.837-.34q1.42 0 2.837.34q1.417.34 2.832 1.018q.61.298.97.838q.361.539.361 1.158v1.646z" />
            </svg></div>
        <div class="logocontent">
            <span>Hello</span>
            <span>Register</span>
        </div>
    </div>
    <div class="heart">
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 256 256">
            <path fill="white"
                d="M223 57a58.07 58.07 0 0 0-81.92-.1L128 69.05l-13.09-12.19A58 58 0 0 0 33 139l89.35 90.66a8 8 0 0 0 11.4 0L223 139a58 58 0 0 0 0-82m-11.35 70.76L128 212.6l-83.7-84.92a42 42 0 0 1 59.4-59.4l.2.2l18.65 17.35a8 8 0 0 0 10.9 0l18.65-17.35l.2-.2a42 42 0 1 1 59.36 59.44Z" />
        </svg>
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24">
            <path fill="white" fill-rule="evenodd"
                d="M12 2.75A2.25 2.25 0 0 0 9.75 5v.26c.557-.01 1.168-.01 1.84-.01h.821c.67 0 1.282 0 1.84.01V5A2.25 2.25 0 0 0 12 2.75m3.75 2.578V5a3.75 3.75 0 1 0-7.5 0v.328c-.143.012-.28.026-.414.043c-1.01.125-1.842.387-2.55.974c-.707.587-1.118 1.357-1.427 2.327c-.3.94-.526 2.147-.81 3.666l-.021.11c-.402 2.143-.718 3.832-.777 5.163c-.06 1.365.144 2.495.914 3.422c.77.928 1.843 1.336 3.195 1.529c1.32.188 3.037.188 5.218.188h.845c2.18 0 3.898 0 5.217-.188c1.352-.193 2.426-.601 3.196-1.529c.77-.927.972-2.057.913-3.422c-.058-1.331-.375-3.02-.777-5.163l-.02-.11c-.285-1.519-.512-2.727-.81-3.666c-.31-.97-.72-1.74-1.428-2.327c-.707-.587-1.54-.85-2.55-.974a11.23 11.23 0 0 0-.414-.043M8.02 6.86c-.855.105-1.372.304-1.776.64c-.403.334-.694.805-.956 1.627c-.267.84-.478 1.958-.774 3.537c-.416 2.217-.711 3.8-.764 5.013c-.052 1.19.14 1.88.569 2.399c.43.517 1.073.832 2.253 1c1.2.172 2.812.174 5.068.174h.72c2.257 0 3.867-.002 5.068-.173c1.18-.169 1.823-.484 2.253-1.001c.43-.518.621-1.208.57-2.4c-.054-1.211-.349-2.795-.765-5.012c-.296-1.58-.506-2.696-.774-3.537c-.262-.822-.552-1.293-.956-1.628c-.404-.335-.92-.534-1.776-.64c-.876-.108-2.013-.109-3.62-.109h-.72c-1.607 0-2.744.001-3.62.11"
                clip-rule="evenodd" />
        </svg>
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24">
            <path fill="white"
                d="m19.6 21l-6.3-6.3q-.75.6-1.725.95T9.5 16q-2.725 0-4.612-1.888T3 9.5q0-2.725 1.888-4.612T9.5 3q2.725 0 4.613 1.888T16 9.5q0 1.1-.35 2.075T14.7 13.3l6.3 6.3zM9.5 14q1.875 0 3.188-1.312T14 9.5q0-1.875-1.312-3.187T9.5 5Q7.625 5 6.313 6.313T5 9.5q0 1.875 1.313 3.188T9.5 14" />
        </svg>
        <img src="" alt="">
    </div>
</div>
</div>
</template>
<style scoped>
.nav {
    display: flex;
    gap: 1rem;
    justify-content: space-between;
    background-color: #678E61;
    color: white;
    padding: 30px;
}
.nav a {
    color: white;
    text-decoration: none;
}
.logo,
.center-nav,
.end-nav,
.endlogo {
    display: flex;
    gap: 1rem;
    justify-content: space-between;
    color: white;
}

.logocontent {
    display: flex;
    flex-direction: column;
}
.heart {
    display: flex;
    justify-content: space-between;
    gap: 1rem;
}

.shop,
.pagess,
.blogs{
    display: flex;

}

.heart svg{
    border: 1px solid white;
    border-radius: 50%;
    padding: 1px;
    background-color: rgb(79, 78, 78);
    opacity: 10%;
    
}

 </style>








