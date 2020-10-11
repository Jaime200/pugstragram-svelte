<script>
export let nickname;
export let name;
</script>
<style>
    .Profile__content {
      display: flex;
      align-items: center;
    }
    .Profile__avatar img {
      width: 42px;
      height: 42px;
      border-radius: 50%;
    }
    .Profile__info {
      margin: 0 0 0 0.5em;
    }
    .Profile__info h2 {
      font-size: 14px;
      color: black;
      margin: 0;
      padding: 0;
    }
    .Profile__info span {
      font-size: 12px;
      font-weight: normal;
    }
  </style>

<div class="Profile">
    <div class="Profile__content">
        <div class="Profile__avatar">
            <img src="https://arepa.s3.amazonaws.com/oscar.png" alt="foto">
        </div>
        <div class="Profile__info">
            <h2>{nickname}</h2>
            <span>{name}</span>
        </div>
    </div>
</div>