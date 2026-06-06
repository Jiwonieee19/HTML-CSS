Exercise - More CSS Features

gridtemplate + media queries power
.grid-video {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    height: 90.6vh;
    background-color: rgb(239, 239, 239);
}

@media (min-width: 751px) and (max-width: 999px) {
    .grid-video {
        grid-template-columns: 1fr 1fr;
    }
}

@media (max-width: 750px) {
    .grid-video {
        grid-template-columns: 1fr;
    }
}
