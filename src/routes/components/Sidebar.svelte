<script>
    import '../../lib/simple_line_icons/css/simple-line-icons.css'
    import logo from '$lib/image/Avatar.png';
</script>
<div class="smol-sidebar">
    <img src={logo} alt="Logo Web">
    <div class="line"></div>
    <span class="icon-home"></span>
    <span class="icon-user"></span>
    <span class="icon-bulb"></span>
    <span class="icon-graduation"></span>
    <span class="icon-grid"></span>
    <span class="icon-phone"></span>
    <span class="icon-social-facebook"></span>
    <span class="icon-social-instagram"></span>
</div>

<style>
    .smol-sidebar{
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
        width: 10px;
        height: 742px;
        position: relative;
        gap: 24px;
        border-radius: 12px;
        background: rgba(0,0,0,0.66);
        backdrop-filter: blur(25.8px);
        padding: 24px;

    }

    .smol-sidebar img{
        width: 44px;
        height: 44px;
        object-fit: cover;
    }

    .line{
        align-self: stretch; 
        height: 2px; 
        border-radius: 2px; 
        background: rgba(255,255,255,0.5);
    }
</style>