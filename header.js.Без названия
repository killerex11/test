makeGet('getNowPlaying.php').then(raw => {
    const data = JSON.parse(raw)

    const band = document.getElementsByClassName('header-nav-stream-live')[0]
    if(data.length > 0){
        band.classList.remove('offline')
        band.classList.add('online')
        band.innerHTML = 'Online'
    }else{
        band.classList.remove('online')
        band.classList.add('offline')
        band.innerHTML = 'Offline'
    }
})
