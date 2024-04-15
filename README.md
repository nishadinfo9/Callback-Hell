# Callback-Hell

function getDeta(data, nextDeta) {
    setTimeout(() => {
        console.log('data = ' + data);
        if (nextDeta) {
        nextDeta();
        }
    }, 2000);
}


getDeta(1 , ()=>{
    console.log('geting deta 2...');
    getDeta(2, ()=>{
        console.log('geting deta 3...');
        getDeta(3, ()=>{
            console.log('geting deta 4...');
            getDeta(4, ()=>{
                console.log('geting deta 5...');
                getDeta(5 , ()=>{
                    console.log('geting deta 6...');
                    getDeta(6, ()=>{
                        console.log('geting deta 7...');
                        getDeta(7, ()=>{
                            console.log('geting deta 8...');
                            getDeta(8, ()=>{
                                console.log('geting deta 9...');
                                getDeta(9 , ()=>{
                                    console.log('geting deta 10...');
                                    getDeta(10, ()=>{
                                        getDeta(11, ()=>{
                                            getDeta(12, ()=>{
                                                getDeta(13 , ()=>{
                                                    getDeta(14, ()=>{
                                                        getDeta(15, ()=>{
                                                            getDeta(16, ()=>{
                                                                getDeta(17 , ()=>{
                                                                    getDeta(18, ()=>{
                                                                        getDeta(19, ()=>{
                                                                            getDeta(20, ()=>{
                                                                                
                                                                            })
                                                                        })
                                                                    })
                                                                })
                                                            })
                                                        })
                                                    })
                                                })
                                            })
                                        })
                                    })
                                })
                            })
                        })
                    })
                })
            })
        })
    })
})
