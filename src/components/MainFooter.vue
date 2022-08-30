<template>
  <footer id="footer" class="page-footer">
    <div class="padding bg-dark b-t">
      <div class="page-container">
        <div class="py-5 text-inherit text-hover-primary">
          <div class="row mb-5">
            <div class="col-12 col-md-3 col-sm-6 col-xs-12">
              <div class="mb-3">
                <a href="#" class="navbar-brand text-white"><img src="../assets/img/logos/nhuzik-logo-inverted.png"
                    alt="" />
                  <span class="hidden-folded d-inline l-s-n-1x">Nhuzik</span></a>
              </div>
              <div class="px-1">
                <p>Portal de Música Moçambicana - Nesta plataforma, encontramos a Bibliografia, a Discografia e todo o
                  esforço artístico dos Moçambicanos nessa área cultural.</p>
              </div>
            </div>
            <div class="col-6 col-md-2 col-sm-6 col-xs-12">
              <ul class="list-unstyled l-h-2x text-highlight">
                <li><a href="#">Artistas</a></li>
                <li><a href="#">Músicas</a></li>
                <li><a href="#">Bibliografias</a></li>
                <li><a href="#">Discografias</a></li>
                <li><a href="#">Logar</a></li>
                <li><a href="#">Registar</a></li>
              </ul>
            </div>
            <div class="col-6 col-md-2 col-sm-6 col-xs-12">
              <ul class="list-unstyled l-h-2x text-highlight">
                <li><a href="#">MMA</a></li>
                <li>
                  <a href="#">Novidades</a>
                </li>
                <li><a href="#">Top Semana</a></li>
                <li><a href="#">Albums</a></li>
                <li><a href="#">Faixas</a></li>
                <li>
                  <a href="#">Playlists</a>
                </li>
              </ul>
            </div>
            <div class="col-12 col-md-2 col-sm-6 col-xs-12">
              <ul class="list-unstyled l-h-2x text-highlight">
                <li><a href="#">Políticas de privacidade</a></li>
                <li><a href="#">Termos e condições</a></li>
                <li><a href="#">Direitos autorais</a></li>
                <li><a href="#">Documentações</a></li>
                <li><a href="#">Actualizações</a></li>
              </ul>
            </div>
            <div class="col-6 col-md-2 col-sm-6 col-xs-12 text-md-right">
              <h5 class="mb-3 text-muted">Siga-nos</h5>
              <a href="#">
                <img class="icon48"
                  src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAYAAACqaXHeAAAABmJLR0QA/wD/AP+gvaeTAAAD5klEQVR4nO2a22tdRRSHvzWzk0h6YoRKfRGkNImWgi+9UESIARVrU8G2/gGFIqEY0GMLagX7oPiiDRipLUL/gIoXTFSKxYKXCtYnpaCnUVHBCvpgElMwOZnlQwO+ZM+e3cw+7k33B/tp1qz5ZZ215paBmpqampqaGxYJNbxtTDcklnERRoFBYF1xsq6LBaClygfLhtd+n5Q/QjoFBWDjId2vwmmgby0KO8icKgd+PiHvZBlmBmDgkO5X5QwgClNGOd7b4OI3r8hCFKmRuPuwrlu4yg5RmgqjgFPhsR8zguANwKYx3WBhBuhDea51Sl6OKbooBsf0qMCLwKzrYnDGUw7G5+imZcYTR1/imKrKHw9w+aS8ZJXpxNHfvcgTPltvAAzssQrGcTyuxOLpWmbCKlhlj88u8TY6NgEs9vB1THGd4B/HxV4BgQGfnTcDrNKwCpdOyN9x5RXP96dl3ioY9a9c3gywLq6oXKjKkxfYqcIDogypsF6u6V0QWET4C+XKxD3yQpqLEP3+EtDcsqPw1AUdNl/yKsJWYPW16j9tqQEI0V+6DDjyuR4U5Q0ytIVQuQx49lMdVjiJYmP4C9HvnwRd57LgmKoxhlMWrAVCPx8h+v0l0MEMcJ+xywp3xvQZor80JWCUh4OPpoFUahJMhJ0ZJucEnl7qZebYNrka4rNSk6BVbve1CzSfGZZv8/isVAZY5RZfe3+D73L7DNCftRXu2ERooNusCFrte3wr7bw+Q/RnHYY6RpZQEcn9U4ToL80yWMRYa18GO5kBBfisM6Bsq8Cb5zRdUobYtL7iuPfgg/LFam2l2wcUkeYov6Q1lW4fYOKnefuObq6kNZYvA+IH4LeREUndH5QuAwoogdT0hwgZEPsXi+1PswJQtuNw9BLwTIBwA5SAwK/e8co2CT76kKTeebz/kWePADyyK71vGqXLAB8FLJHlmwS9YxXhs1KHoQKCXa3DUBE+6wwIsPE11sfhil+IlG4f4KOIZbBS+4BCSqBKGVDInWCdAdk2Wf8YmbcKZ7ZoI5Yoz1jeLy8fDujNK33nfHZZAfghUeiB7fkl5GMt7wBWo93DtkQhUWZ8dv4ALDNlHSSO5nVoyIVR/5cXC82VBxJT3nG9jUtMJspcAqNnN+vR/DLCiVkCZzfr84ljd6LM9rZ53Webecb++C7dK8pbgEGZFmHCJHw1cinu28Gf3vbfB2zc578POL9FG67NDhWaKLsBh7Lv/pa85+sXdMnwyaDulWvP5ftD7EvArMCB+1rybpZh8C3L+SG9tcsxvvIUfQgofGXIyTxwWWB6yTA50pI//29BNTU1NTU1JedfST9jWXvBx2EAAAAASUVORK5CYII=" />
              </a>
              <a href="#">
                <img class="icon52"
                  src="data:image/png;base64,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"
                  alt="Youtube" title="Youtube" />
              </a>
              <a href="#">
                <img class="icon48"
                  src="data:image/png;base64,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" />
              </a><br>
              <a href="#">
                <img class="icon48"
                  src="data:image/png;base64,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"
                  alt="Instagram" title="Instagram" />
              </a>
              <a href="#">
                <img class="icon48"
                  src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAYAAACqaXHeAAAABmJLR0QA/wD/AP+gvaeTAAAEh0lEQVR4nO2aTWhcVRTHf/fdN2mqiVBw1WhxoZNFFg2YtG4SmWoLkgRBcSCKETcN2rgwG79aUIm6kXRjRdOVRaskVqpJhGKT0MaATetKJIQWAoXalV1IWtKZ995xMQlOJpnc+zJvPorvB3cxN+fe87/3nXfuRx7ExMTExMTE/F9RtoZ73pAeEQaBduD+8kkqidtKmAeGr59QEzYNrCbgkSPyMcI7JUmrMAo+WvpcHbWw25pHX5cehJ+AjFIccxy+XvxM/RWJyohpHpDdvs/LwIdAnRJ6rn5hFwnFO+2XmeZ+keZ+eSsSlRUgeVjeXtU8ZbJ1TAau0OYKOMKpaOSVHw1fuQKu0G6yNU6ADmjQASyMqJvRyCs/CyPqpg5ABzSabF2jgUQjqtLY6jZOgA5KlVIdbHXHEWAyiCOgQhHw6Zy3ztPOjG48klLL2+3PVrd5GQxypdLccbMtpbS31W1eBiVXys2an7XiKuelKPozUTMRUDgBWjh8fC7Tut3+7r0ICDaUHXWeM3FiZnuTYKvbnAQr9P4XEduEci59ecEbEZHTvrh/NGaQ2wmv9bUDibmt+rPVXTPL4BZPqw5hANSAxuduHbi5Q+yWJ9l7bhmM+jWLbBlceyfLzYYkGNCjYWmT5Gg1Wba6bY7DFYmCwgG+8rQ7sUfppAtpR/hGB1zTwh0tLGuRhah0VyQHnD6XPegolQ6UdChRDwFu7yG33uQnlVIeMLZaQlETOeC785J0fP8k0ImAI8XzVrVyQNki4My5bCeef1Zgl429E/EEVDUCfpiUpAr8s1gOHmp4FdjOVthV3kktskuLkFfGXSR1n6MbsvV6w1VVgW04hyXoNr8CIbVMTmYPInQWVL/b1ZX4JEo/Jmz7i3wrrAOVhv+8C4w/07P14HPtwvkxEd1WOOST0SId6yoUw3btwvmJqr/oI0Boyv+tVtwrlu0ipYoRsP63jY7ffpYH7ma8/Kp/wnk16yhG5KuAFm7kb2kTOzzjf2f8Fa8tv40j3LD3uDlVuxDRoi6u29f7DJraKBhcN2miLtp7LKajSldirshowcGm+9L32feK2c+fyR51ha78NgoZtfdYmu7Ic0D784nzv49lLwg8mVc9dGUs+4QSjtfjzgOs4O0TxSABXQVdTLe9kJgO53UjVVsFAFzxXg1yA30wr7ob6M6QS3YO5G8X1rgV4PeH97iJBkvdZbkQ2ZveueT4PKeFW8UuNDYpfyt49vF0/bVw3krTXbYLkb29iVmt/P1amDEOHqaV+Ptb04lfw3sqTXdZb4Vbck/zwJ/fZp9CqTRIB/Dw6p+vg5olkNGWF0t/5wup2kZoM1p6E1OA8XOVKKlqEqwFaioCqkEcAXEE2NnZ7AOW3QB+bJbdpYqqFONJaVrdChtPleZ9AFzWAvWKvmjklR/XoU8LOAHGuwibHDCMkAI++CUpiOLUocXa/FR2KilN4tCH8D4CEphvo6w+lp5pliGEoie6mkQxlFpUx8xmlsw+Jt1KeFNgH9BQkrjysaxgPlAMd15Vk9UWExMTExMTE1Pb/AsI8vFlya+T9QAAAABJRU5ErkJggg=="
                  alt="TikTok" title="TikTok" />
              </a>
              <a href="#">
                <img class="icon48"
                  src="data:image/png;base64,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"
                  alt="WhatsApp" title="WhatsApp" />
              </a>
            </div>
          </div>
          <div class="text-center">
            <span class="text-muted text-sm">Nhuzik &copy; Todos Direitos Reservados - <a
                href="https://keomagroup.netlify.app/" target="_blank">Keoma Software, Inc</a></span>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
</style>