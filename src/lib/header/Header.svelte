<script lang="ts">
  import {
    Navbar,
    NavbarToggler,
    NavbarBrand,
    Nav,
    NavItem,
    NavLink,
    Icon,
  } from 'sveltestrap';
</script>

<Navbar color="dark" expand="md">
  <NavbarBrand href="/">sveltestrap</NavbarBrand>
  <Icon name="globe2" />
  <Nav class="ms-auto" navbar>
    <NavItem>
      <NavLink href="#">Components</NavLink>
    </NavItem>
  </Nav>
</Navbar>